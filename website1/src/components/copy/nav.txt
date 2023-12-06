import { useState } from 'react';
import { FontAwesomeIcon } from '@fortawesome/react-fontawesome';
import { faBars, faXmark } from '@fortawesome/free-solid-svg-icons';

import { Link } from 'react-scroll';


const Navbar = () => {
  const [nav, setNav] = useState(false)
  const handleClick = () => setNav(!nav)

  const handleClose = () => setNav(!nav)

  return (
    <div className="w-screen h-[80px] z-10 bg-zinc-200 fixed drop-shadow-lg lg:relative">
      <div className="px-2 flex justify-between item-center w-full h-full">
        <div className="flex items-center">
          <h1 className="text-3xl font-bold mr-4 sm:text-4xl">D.Cloud.</h1>
          <ul className="hidden md:flex gap-16 lg:mx-10 font-semibold cursor-pointer">
            {/* React scroll */}

            <li><Link to="Home" smooth={true} offset={0} duration={500}>Home</Link></li>
            <li><Link to="About" smooth={true} offset={-100} duration={500}>About</Link></li>
            <li><Link to="Support" smooth={true} offset={-0} duration={500}>Support</Link></li>
            <li><Link to="Platforms" smooth={true} offset={-40} duration={500}>Platforms</Link></li>
            <li><Link to="Pricing" smooth={true} offset={60} duration={500}>Pricing</Link></li>

            
          </ul>
        </div>
        <div className="hidden md:flex w-[260px] mr-2 md:mr-0">
          <button className="button-47 mt-3">Sign In</button>
          <button type="button" className="button-36 m-2">
            Sign Up
          </button>
        </div>
        <div
          className="md:hidden mr-4 flex justify-center items-center"
          onClick={handleClick}
        >
          {!nav ? (
            <FontAwesomeIcon className="w-5" icon={faBars} />
          ) : (
            <FontAwesomeIcon className="w-5" icon={faXmark} />
          )}
        </div>
      </div>

      
      {/* mobile nav */}
      <ul className={!nav ? 'hidden' : 'absolute bg-zinc-200 text-center w-full px-8 cursor-pointer'}>
            <li className="border-b-2 border-zinc-300 w-full"><Link onClick={handleClose} to="Home" smooth={true} offset={0} duration={500}>Home</Link></li>
            <li className="border-b-2 border-zinc-300 w-full"><Link onClick={handleClose} to="About" smooth={true} offset={-160} duration={500}>About</Link></li>
            <li className="border-b-2 border-zinc-300 w-full"><Link onClick={handleClose} to="Support" smooth={true} offset={-50} duration={500}>Support</Link></li>
            <li className="border-b-2 border-zinc-300 w-full"><Link onClick={handleClose} to="Platforms" smooth={true} offset={-100} duration={500}>Platforms</Link></li>
            <li className="border-b-2 border-zinc-300 w-full"><Link onClick={handleClose} to="Pricing" smooth={true} offset={-50} duration={500}>Pricing</Link></li>

        <div className="my-4">
          <button className="button-47 m-1 text-indigo-600 px-8 py-3">
            Sign In
          </button>
          <button className="button-36 m-1 block w-full">Sign Up</button>
        </div>
      </ul>
    </div>
  );
}
export default Navbar
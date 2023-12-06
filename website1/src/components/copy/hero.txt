// import React from 'react'
import { FontAwesomeIcon } from '@fortawesome/react-fontawesome';
import { faCloudArrowUp, faDatabase, faPaperPlane, faChartLine } from '@fortawesome/free-solid-svg-icons';

import bgImg from '../assets/img/pic-1.svg';

const Hero = () => {
  return (
    <div name="Home" className="w-screen h-screen lg:h-auto bg-zinc-200 top-[80px] flex flex-col justify-between lg:absolute md:absolute">
      <div className="grid md:grid-cols-2 m-auto">
        <div className="flex flex-col justify-center md:items-start w-full px-5 pt-28 py-8 lg:p-32">
          <p className="text-2xl font-medium">Unique Sequencing & Production</p>
          <h1 className="py-3 text-5xl md:text-7xl font-bold">Cloud Managment</h1>
          <p className="text-2xl font-medium">This Is Our Tech Brand.</p>
          <button className="button-36 py-3 px-6 w-[90%] my-4">
            Get Started
          </button>
        </div>
        <div>
          <img
            className="w-full sm: mx-5 lg:p-32 lg:m-0"
            src={bgImg}
            alt="ciber-security img"
          />
        </div>
        <div className="abolute md:relative flex flex-col py-8 md:min-w-[760px] mx-1 transform lg:top-[-100px] lg:left-[42%] bg-zinc-200 border border-slate-300 rounded-xl text-center shadow-xl">
          <p className='font-bold'>Data Services</p>
          <div className="flex justify-between flex-wrap px-4">
            <p className="flex px-4 py-2 text-slate-500">{''}<FontAwesomeIcon className="h-6 mx-1 text-indigo-600" icon={faPaperPlane}/>{' '}App Security</p>
            <p className="flex px-4 py-2 text-slate-500">
              {' '}
              <FontAwesomeIcon
                className="h-6 mx-1 text-indigo-600"
                icon={faChartLine}
              />{' '}
              Dashboard Design
            </p>
            <p className="flex px-4 py-2 text-slate-500">
              {' '}
              <FontAwesomeIcon
                className="h-6 mx-1 text-indigo-600"
                icon={faCloudArrowUp}
              />{' '}
              Cloud Data
            </p>
            <p className="flex px-4 py-2 text-slate-500">
              {' '}
              <FontAwesomeIcon
                className="h-6 mx-1 text-indigo-600"
                icon={faDatabase}
              />
              API Integration
            </p>
          </div>
        </div>
      </div>
    </div>
  );
};
export default Hero;



// import React from 'react'

import { faCheck } from "@fortawesome/free-solid-svg-icons"
import { FontAwesomeIcon } from "@fortawesome/react-fontawesome"

const AllInOne = () => {
  return (
    <div name="Platforms" className="w-full my-32 absolute lg:top-[2300px] top-[3600px]">
      <div className="max-w-[1240px] mx-auto px-2">
        <h2 className="text-5xl font-bold text-center">All-In-One Platform</h2>
        <p className="text-2xl py-8 text-gray-500 text-center">
          Lorem ipsum dolor sit amet consectetur adipisicing. Velit, deleniti
          rerum quisquam dolore.
        </p>

        <div className="grid sm:grid-cols-2 lg:grid-cols-4 gap-4 pt-4">
          
          {/* item-1 */}

          <div className="flex">
            <div>
              <FontAwesomeIcon
                className="w-7 mr-4 text-green-600"
                icon={faCheck}
              />
            </div>

            <div>
              <h3 className="font-bold text-lg">Notifications</h3>
              <p className="text-lg pt-2 pb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit nemo voluptatem dolore fuga impedit rem?</p>
            </div>
          </div>

          {/* item-2 */}

          <div className="flex">
            <div>
              <FontAwesomeIcon
                className="w-7 mr-4 text-green-600"
                icon={faCheck}
              />
            </div>

            <div>
              <h3 className="font-bold text-lg">Notifications</h3>
              <p className="text-lg pt-2 pb-4">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sed sint voluptatibus provident iure maiores ipsa!
              </p>
            </div>
          </div>

          {/* item-3 */}

          <div className="flex">
            <div>
              <FontAwesomeIcon
                className="w-7 mr-4 text-green-600"
                icon={faCheck}
              />
            </div>

            <div>
              <h3 className="font-bold text-lg">Notifications</h3>
              <p className="text-lg pt-2 pb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. In veritatis aut a praesentium, beatae eveniet?
              </p>
            </div>
          </div>

          {/* item-4 */}

          <div className="flex">
            <div>
              <FontAwesomeIcon
                className="w-7 mr-4 text-green-600"
                icon={faCheck}
              />
            </div>

            <div>
              <h3 className="font-bold text-lg">Notifications</h3>
              <p className="text-lg pt-2 pb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem, voluptatem mollitia omnis hic repudiandae in!
              </p>
            </div>
          </div>
          

          {/* item-5 */}

          <div className="flex">
            <div>
              <FontAwesomeIcon
                className="w-7 mr-4 text-green-600"
                icon={faCheck}
              />
            </div>

            <div>
              <h3 className="font-bold text-lg">Notifications</h3>
              <p className="text-lg pt-2 pb-4">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Maiores quis hic molestiae doloremque provident. Eveniet.
              </p>
            </div>
          </div>

          {/* item-6 */}

          <div className="flex">
            <div>
              <FontAwesomeIcon
                className="w-7 mr-4 text-green-600"
                icon={faCheck}
              />
            </div>

            <div>
              <h3 className="font-bold text-lg">Notifications</h3>
              <p className="text-lg pt-2 pb-4">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ex, repellendus voluptatem illum quae voluptate sequi!
              </p>
            </div>
          </div>

          {/* item-7 */}

          <div className="flex">
            <div>
              <FontAwesomeIcon
                className="w-7 mr-4 text-green-600"
                icon={faCheck}
              />
            </div>

            <div>
              <h3 className="font-bold text-lg">Notifications</h3>
              <p className="text-lg pt-2 pb-4">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Modi voluptas ea qui optio ex facilis?
              </p>
            </div>
          </div>

          {/* item-8 */}

          <div className="flex">
            <div>
              <FontAwesomeIcon
                className="w-7 mr-4 text-green-600"
                icon={faCheck}
              />
            </div>

            <div>
              <h3 className="font-bold text-lg">Notifications</h3>
              <p className="text-lg pt-2 pb-4">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ratione commodi quo saepe qui itaque quasi?
              </p>
            </div>
          </div>
          
        </div>
      </div>
    </div>
  );
}
export default AllInOne
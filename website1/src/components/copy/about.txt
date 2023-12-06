// import React from 'react'

const About = () => {
  return (
    <div name="About" className="max-w-[1240px] mx-auto absolute top-[900px] left-12 h-screen lg:ml-70 sm: mt-20 sm: p-5">
      <div className="text-center">
        <h2 className="text-5xl font-bold capitalize">
          Trusted by developers Across the World
        </h2>
        <p className="text-3xl py-6 text-gray-500">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis
          quas porro incidunt eveniet autem commodi ratione vitae aliquam
          excepturi laborum?
        </p>
      </div>

      <div className="grid md:grid-cols-3 px-2 gap-1 lg:ml-24 text-center">
        <div className="border py-8 rounded-xl shadow-xl">
          <p className="text-6xl font-bold text-indigo-600">100%</p>
          <p className="text-gray-400 mt-2">Complition</p>
        </div>

        <div className="border py-8 rounded-xl shadow-xl">
          <p className="text-6xl font-bold text-indigo-600">24/7</p>
          <p className="text-gray-400 mt-2">Delivery</p>
        </div>

        <div className="border py-8 rounded-xl shadow-xl">
          <p className="text-6xl font-bold text-indigo-600">100K</p>
          <p className="text-gray-400 mt-2">Transactions</p>
        </div>
      </div>
    </div>
  );
};
export default About;
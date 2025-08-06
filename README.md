##  marina
## personal

import Image from "next/image";

export default function Home() {
  return (
    <main className="min-h-screen bg-gradient-to-br from-purple-200 via-white to-indigo-200 $
      <div className="max-w-3xl mx-auto bg-white rounded-2xl shadow-xl p-8 text-center">
        <h1 className="text-4xl font-bold text-purple-700 mb-4">Hi, I'm Marina!</h1>
        <p className="text-lg text-gray-700 mb-6">Here are some fun facts about me:</p>

        <ul className="text-left list-disc list-inside space-y-2 text-gray-600">
          <li>I love mentoring people and building team culture 🌱</li>
          <li>I love helping customers 😅</li>
          <li>I've worked on observability, AI adoption, and career growth programs 🧠</li>            <li>I xxxx ⚙️</li>
        </ul>

        <div className="mt-8">
          <Image
            src="/images/cat.png"
            alt="My Cat"
            width={300}
            height={300}
            className="rounded-xl shadow-md mx-auto"
          />
          <p className="text-sm text-gray-500 mt-2">Photo of my cats, Juju and Pat 😺</p>
        </div>

        <div className="mt-10 space-y-4">
          <div className="space-x-4">
            <a
              href="/resume.pdf"
              target="_blank"
              rel="noopener noreferrer"
              className="inline-block bg-indigo-600 text-white px-6 py-3 rounded-xl hover:bg$
            >
              View My Resume
            </a>

            <a
              href="https://www.linkedin.com/in/YOUR-LINKEDIN-ID"
              target="_blank"
              rel="noopener noreferrer"
              className="inline-block bg-blue-600 text-white px-6 py-3 rounded-xl hover:bg-b$
            >
              View My LinkedIn
            </a>
          </div>

          <div>
            <a
              href="/gallery"
              className="inline-block bg-purple-600 text-white px-4 py-2 rounded-xl hover:bg$
            >
              More cat photos here
            </a>
          </div>

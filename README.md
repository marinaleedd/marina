##  marina
## personal
import Image from "next/image";

export default function Home() {
  return (
    <main className="min-h-screen bg-gradient-to-br from-purple-200 via-white to-indigo-200 p-8">
      <div className="max-w-3xl mx-auto bg-white rounded-2xl shadow-xl p-8 text-center">
        <h1 className="text-4xl font-bold text-purple-700 mb-4">Hi, I'm Marina Lee!</h1>
        <p className="text-lg text-gray-700 mb-6">Here are some fun facts about me:</p>

        <ul className="text-left list-disc list-inside space-y-2 text-gray-600">
          <li>I love mentoring people and building team culture 🌱</li>
          <li>I bla bla bla  😅</li>
          <li>I've worked on observability, AI adoption, and career growth programs 🧠</li>
          <li>I love cats </li>
        </ul>

        <div className="mt-8">
          <Image
            src="https://images.unsplash.com/photo-1503023345310-bd7c1de61c7d"
            alt="A fun placeholder image"
            width={600}
            height={400}
            className="rounded-xl shadow-md mx-auto"
          />
          <p className="text-sm text-gray-500 mt-2">Photo by Unsplash – because I also like clean design ✨</p>
        </div>

        <div className="mt-10">
          <a
            href="/resume.pdf"
            target="_blank"
            rel="noopener noreferrer"
            className="inline-block bg-indigo-600 text-white px-6 py-3 rounded-xl hover:bg-indigo-700 transition mb-4"
          >
            View My Resume
          </a>
        </div>

        <div className="mt-10">
          <h2 className="text-2xl font-semibold text-purple-700 mb-4">Meet My Cats 🐾</h2>
          <div className="grid grid-cols-1 md:grid-cols-2 gap-6">
            <Image
              src="https://images.unsplash.com/photo-1592194996308-7b43878e84a6"
              alt="Cat 1"
              width={300}
              height={300}
              className="rounded-xl shadow-md mx-auto"
            />
            <Image
              src="https://images.unsplash.com/photo-1603318822749-ff3729ff1eac"
              alt="Cat 2"
              width={300}
              height={300}
              className="rounded-xl shadow-md mx-auto"
            />
          </div>
        </div>

        <div className="mt-10">
          <a
            href="https://vercel.com"
            target="_blank"
            rel="noopener noreferrer"
            className="inline-block bg-purple-600 text-white px-6 py-3 rounded-xl hover:bg-purple-700 transition"
          >
            Deployed with Vercel
          </a>
        </div>
      </div>
    </main>
  );
}

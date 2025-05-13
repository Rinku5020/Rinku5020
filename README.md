import React from "react";

const GitHubProfile = () => {
  return (
    <div className="min-h-screen bg-gray-900 text-white flex flex-col items-center p-6">
      {/* Header / Banner */}
      <div className="w-full max-w-4xl bg-white text-black rounded-xl shadow-lg overflow-hidden">
        <div className="flex flex-col md:flex-row p-6 items-center justify-between">
          <div className="space-y-2 text-center md:text-left">
            <h1 className="text-3xl font-bold font-serif">Jay Mistry</h1>
            <p className="text-sm">SOFTWARE DEVELOPER</p>
            <div className="flex flex-col sm:flex-row sm:space-x-4 text-sm mt-2">
              <span>📞 +91 7500990024</span>
              <span>✉️ 5020rinkunimaje@gmail.com</span>
              <span>🌐 <a href="https://www.ramira.in" className="text-blue-600 hover:underline">www.ramira.in</a></span>
            </div>
          </div>
       
        </div>
      </div>

      {/* Main Content */}
      <div className="mt-10 text-center">
        <h2 className="text-2xl font-bold">Hi, I'm Jay 👋</h2>
        <p className="mt-4 text-lg font-medium">
          A passionate Software Developer from Surat
        </p>
        <div className="mt-4 text-base">
          <p>💼 I'm currently working on <strong>Accounting & Tax Software</strong></p>
          <p>📚 I'm currently learning <strong>Microsoft SQL</strong> and <strong>Delphi</strong></p>
        </div>
      </div>
    </div>
  );
};

export default GitHubProfile;


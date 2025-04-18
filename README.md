Team Posts Feed (React UI Component Project) 👥📝

This project is a social-style team feed built using React.Each post includes a profile, title, content (image or code), interactive icons, and reply sections.

🔗 Live Demo

Click here to try the app live 🚀

🛠 Technologies Used

React (JSX components)

JavaScript (ES6+)

CSS3 (modular or inline)

Lucide icons (lucide-react package)

🌟 Features

User profile display with timestamp

Dynamic post content (code, image, or text)

Emoji reactions (smile, heart, thumbs up)

"Reply" input field per post

“Start a post” section at the bottom

Click-based UI elements (onClick events used for reactions, expanding content, etc.)

💡 Educational Purpose

This project was built as part of learning to:

Map through arrays of post data

Use onClick handlers for interactivity

Conditionally render different types of content

Practice structuring reusable React components

🧪 How to Run

Clone this repository:

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

Install dependencies:

npm install

Start the development server:

npm run dev

Open http://localhost:3000 in your browser

🔔 Icons (Lucide React)

This project uses modern icons from lucide-react for visual elements like the vertical dots menu, reaction icons, etc.

✅ Installation

If not already installed, run:

npm install lucide-react

Or using Yarn:

yarn add lucide-react

🚀 Usage

Import the icons you need in your components like this:

import { MoreVertical, Heart, Smile } from "lucide-react";

function PostFooter() {
  return (
    <div>
      <MoreVertical size={20} />
      <Heart size={20} />
      <Smile size={20} />
    </div>
  );
}

You can customize size, color, stroke width, and more.See full icon list at 👉 lucide.dev/icons

📌 Status

🔧 Work in Progress🗓️ Last updated: April 2025

Made with 💻 by Tsetsen


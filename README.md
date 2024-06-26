<div align="center">
  <br/>
  <br/>
  <img src="/public/logo-dark.png#gh-dark-mode-only" alt="logo" width="200" height="auto" />
  <img src="/public/logo-light.png#gh-light-mode-only" alt="logo" width="200" height="auto" />
  <br/>
  <br/>

  <h3>
    <a href="https://the-wild-oasis.vercel.app">
      <strong>Demo Website</strong>
    </a>
  </h3>

  <hr>

</div>

<!-- Badges -->
<div align="center">

<img src="https://img.shields.io/badge/Status-Completed-success?style=flat" alt="Status" />

</div>

<!-- Brief -->
<p align="center">
The Wild Oasis hotel management app is a full-featured React web application that allows hotel employees to manage cabins, bookings, and guests. The app uses Supabase for its backend and implements a variety of advanced React techniques, such as HOCs, the Compound Component Pattern, and React Query.
</p>

## Table of contents

- [Features](#Features)
- [Screenshots](#Screenshots)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Installation](#installation)

## Features

1. **User Authentication and Signup:**

   1. Hotel employees can log in to the application to perform tasks.
   2. New users can only be signed up within the application to ensure that only actual hotel employees can create accounts.

2. **User Profile Management:**

   1. Users can upload an avatar to personalize their profile.
   2. Users can change their name and password.

3. **Cabin Management:**

   1. The app provides a table view with all cabins.
   2. The table view displays cabin information, including cabin photo, name, capacity, price, and current discount.
   3. Users can update or delete existing cabins.
   4. Users can create new cabins, including the ability to upload a photo.

4. **Booking Management:**

   1. The app provides a table view with all bookings.
   2. The table view displays booking information, including arrival and departure dates, booking status, paid amount, cabin details, and guest data.
   3. Booking status can be "unconfirmed," "checked in," or "checked out."
   4. The table view is filterable by booking status.
   5. Additional booking data includes the number of guests, number of nights, guest observations, and whether breakfast was booked and its price.

5. **Booking Operations:**

   1. Users can delete, check in, or check out a booking as the guest arrives.
   2. On check-in, users can accept payment outside the app and then confirm the payment within the app.
   3. Guests can add breakfast for the entire stay during check-in if they haven't already.

6. **Guest Data Management:**

   1. Guest data contains full name, email, national ID, nationality, and a country flag for easy identification.

7. **Dashboard:**

   1. The initial app screen serves as a dashboard displaying important information for the last 7, 30, or 90 days.
   2. It shows a list of guests checking in and out on the current day, and users can perform tasks related to these activities from the dashboard.
   3. The dashboard provides statistics on recent bookings, sales, check-ins, and occupancy rates.
   4. It includes a chart showing all daily hotel sales, distinguishing between "total" sales and "extras" sales (only breakfast at present).
   5. There's also a chart displaying statistics on stay durations, an important metric for the hotel.

8. **Application-wide Settings:**

   1. Users can define application-wide settings such as breakfast price, minimum and maximum nights per booking, and maximum guests per booking.

9. **Dark Mode:**
   1. The app includes a dark mode option for a different visual appearance and enhanced user experience in low-light conditions.

<br/>

## :camera: Screenshots

<kbd><img width="890" alt="login" src="https://github.com/sudeepmahato16/the-wild-oasis/assets/122378993/6648f02d-fb01-46ac-810c-fa47066e83ff"></kbd>

<kbd><img width="957" alt="dashboard" src="https://github.com/sudeepmahato16/the-wild-oasis/assets/122378993/77754290-4df7-42ee-9e13-66748d596cff"></kbd>

<kbd><img width="956" alt="bookings" src="https://github.com/sudeepmahato16/the-wild-oasis/assets/122378993/fa04e745-4b44-41d9-b293-53c63545ea9b"></kbd>

<kbd><img width="957" alt="single-booking" src="https://github.com/sudeepmahato16/the-wild-oasis/assets/122378993/33d830fd-6887-467e-b79f-cab427f33680"></kbd>

<br/>

## My process

### Built with

- React
- Supabase
- React Query
- React Router
- React Hook Form
- React Hot Toast
- Recharts
- Styled Components
- Vite

### What I Learned

- **React Fundamentals:** I gained a solid understanding of React, including components, state management, and routing, allowing me to build dynamic user interfaces.

- **Authentication and User Management:** I implemented user authentication using Supabase, ensuring secure access for hotel employees and learned to manage user profiles effectively.

- **Form Handling:** I became proficient in managing forms with React Hook Form, simplifying form validation, submission, and data handling.

- **Data Fetching and Caching:** React Query was employed to fetch and cache data, enhancing the performance and responsiveness of the application.

- **Real-time Updates:** I integrated real-time data updates using Supabase, enabling instant changes to cabin and booking data.

- **Responsive UI Design:** Styled Components were used to create responsive and visually appealing user interfaces that adapt to various screen sizes.

- **Toast Notifications:** React Hot Toast added user-friendly notifications for various actions within the app, improving the overall user experience.

- **Data Visualization:** Recharts was employed for creating charts and visual representations of vital statistics, aiding in data analysis and decision-making.

- **Routing and Navigation:** React Router facilitated smooth navigation and seamless transitions between different views and pages within the application.

- **Settings Management:** I learned to allow users to configure application-wide settings, such as breakfast pricing and booking constraints.

- **Higher-Order Components (HOC):** I utilized Higher-Order Components to enhance code reusability and share common functionalities among multiple components.

- **Compound Component Pattern:** I implemented the Compound Component Pattern to create cohesive and reusable component groups, improving the organization and maintainability of the code.

- **Dark Mode Implementation:** Dark mode was implemented to offer users a personalized visual experience and accommodate different preferences.

- **Git Version Control:** I practiced effective version control using Git, allowing for code management, and tracking project changes.

- **Project Planning and Management:** I gained experience in planning and managing a large-scale project, including feature development, bug fixing, and testing.

By building "The Wild Oasis" project with these technologies and concepts, I've developed a comprehensive set of skills and knowledge that can be applied to future projects and real-world scenarios. This experience has not only expanded my technical expertise but also improved my problem-solving capabilities.

### Installation

- Clone this repo:

```sh
git clone https://github.com/osama206/The-wild-oasis.git
```

- Install dependencies:

```sh
npm install
```

- Build command:

```sh
npm run build
```

- Live server:

```sh
npm run dev
```

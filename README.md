![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# ChronoQuest - Time Travel Booking System

**ChronoQuest** is an innovative time travel booking system designed to provide users with an immersive and unforgettable experience in different eras. Whether you dream of exploring ancient civilizations, witnessing historic events, or venturing into the future, ChronoQuest makes it possible. Our state-of-the-art technology and dedicated team ensure a seamless journey through time. 

This project includes a detailed main page with information on top destinations, a step-by-step guide on how it works, user reviews, and a contact page. With ChronoQuest, you can book tomorrow and enjoy yesterday!

**Please Note:** ChronoQuest is a fictional concept for a time travel agency, created to explore the exciting possibilities that time travel might offer if it becomes possible in the future. This project is a creative representation and not a real-time travel service.

### [Visit ChronoQuest](https://tibssy.github.io/time-travel-agency)


  ![amiresponsive](https://github.com/tibssy/time-travel-agency/assets/72749248/61fb9994-a020-4a71-949e-675a18d81798)

## Table of Contents

- [User Experience](#user-experience)
- [Features](#features)
- [Design](#design)
- [Testing](#testing)

## User Experience

### Ideal User Demographic

**ChronoQuest is perfect for:**

- **New Users:**
  - People who love history and want to experience different eras.
  - Tourists looking for unique and educational travel experiences.
  - Students and teachers interested in learning about different historical periods.
  - Families wanting fun and memorable vacations.
  - Sci-fi fans curious about time travel.

- **Current Users:**
  - Returning customers who enjoyed a ChronoQuest journey and want to explore new destinations.
  - Users looking for updates on new destinations and features.
  - Regular visitors wanting to leave reviews and share their experiences.


### Goals for First-Time Visitors

As a first-time visitor to ChronoQuest, I want to:

- Easily understand what the business is about.
- Navigate the site easily using familiar menus and icons.
- Explore the top time travel destinations and read descriptions.
- Learn how the time travel booking process works.
- Read user reviews to see what others think.
- Find contact information to ask questions or get help.

### Goals for Returning Visitors

As a returning visitor to ChronoQuest, I want to:

- Check for new destinations or updates to packages.
- Read the latest user reviews and experiences.
- Revisit the booking page to plan my next trip.
- Access my previous bookings and travel history.
- Contact customer support for any questions or feedback.


## Features

### Navbar

- **Transparent Navbar:** 
  - The navbar has a transparent blur effect that turns opaque when the mouse hovers over it, enhancing user experience and visibility.

    ![navbar](https://github.com/tibssy/time-travel-agency/assets/72749248/55d74665-7071-4a0e-b9c3-8447c6ac6930)

- **Responsive Mobile Menu:**
  - On mobile devices, the menu is also transparent and blurred. It opens with a smooth animation involving scaling and opacity changes, appearing from under the navbar.

    ![nav-menu](https://github.com/tibssy/time-travel-agency/assets/72749248/7922d77b-d07a-4a12-98a5-ab6647624b66)


### Hero Image

- **Dynamic Hero Image:**
  - The hero image section functions like a slideshow with a fading effect. Three images cycle through every 90 seconds.
  - Each image fades in over 4.5 seconds, starting with a sepia tone. Over the next 25 seconds, the image transitions to full color and scales up by 20%. After 30 seconds, the image starts to fade out as the next image begins to fade in.

    ![hero-slide-1](https://github.com/tibssy/time-travel-agency/assets/72749248/f7db2add-10f4-4f4a-8f80-5c1f4899eb94)

    ![hero-slide-2](https://github.com/tibssy/time-travel-agency/assets/72749248/50a1837e-695d-4d85-b466-acbc5be46d75)

    ![hero-slide-3](https://github.com/tibssy/time-travel-agency/assets/72749248/d39e0c1b-582d-4c42-a136-74a159f5cb36)

### Company Video

- **Informative Video:**
  - A video about the company and the concept of time travel is available, utilizing lazy loading to save network traffic.
  - The video features a thumbnail image for initial display and user controls for play, pause, and volume adjustment.

### Top Destinations Slideshow

- **Past Destinations:**
  - The first slide showcases three top destinations from the past, highlighting historical adventures.
- **Future Destinations:**
  - The second slide features three destinations from the future, offering a glimpse into upcoming adventures.

  ![destenation-slide](https://github.com/tibssy/time-travel-agency/assets/72749248/e6f6c918-698d-4542-92dd-861c478682aa)

### Booking Page

- **Seamless Booking Experience:**
  - The booking page allows users to choose a time period, fill in their personal details, and select their desired destination. 
  - Users can specify if they want to travel to a BC or AD era and input the specific year they want to visit.

### User Reviews

- **Dynamic Review Cards:**
  - Users can view testimonials from other travelers, complete with usernames and photos. 
  - Reviews highlight the experiences and satisfaction of previous users.


## Design

ChronoQuest focuses on simplicity and elegance in its design. The main page features a clean layout with vibrant images and intuitive navigation. The booking page is straightforward, allowing users to select their preferred time period, fill in their details, and confirm their journey quickly. The contact page includes a Google Map iframe for easy location selection.


## Testing

### Lighthouse Performance Tests

Lighthouse was used to test the performance, accessibility, best practices, and SEO of the ChronoQuest website on both mobile and desktop platforms.

- **Desktop Results:**

  ![desktop](https://github.com/tibssy/time-travel-agency/assets/72749248/65f1566c-8a8a-40b4-b5e7-a5682cbf5442)

- **Mobile Results:**

  ![mobile](https://github.com/tibssy/time-travel-agency/assets/72749248/430347c9-13c9-43b9-8270-be8dc080c7f7)


### HTML Validation

The HTML code was validated using the W3C Markup Validation Service to ensure it is error-free and follows best practices.

- **HTML Validation Results:**
  
  ![html-val-index](https://github.com/tibssy/time-travel-agency/assets/72749248/905a9090-df67-4ea9-8f46-20bfafdc64a0)

  ![html-val-booking](https://github.com/tibssy/time-travel-agency/assets/72749248/949b2f18-f31d-4dff-afca-f918f96fb5c8)

  ![html-val-review](https://github.com/tibssy/time-travel-agency/assets/72749248/a01eea37-505f-4135-bb87-1b6635280a2b)

  ![html-val-contact](https://github.com/tibssy/time-travel-agency/assets/72749248/d4c90a78-2e79-4fdf-b41e-7e0bc0bcd5ad)

### CSS Validation

The CSS code was validated using the W3C CSS Validation Service to ensure there are no errors and it adheres to best practices.

- **CSS Validation Results:**

  ![css-val](https://github.com/tibssy/time-travel-agency/assets/72749248/b3c776a8-b0df-4d49-af5c-21976bbd0947)

- **CSS Validation Warnings:**

  ![css-val-warnings](https://github.com/tibssy/time-travel-agency/assets/72749248/5f04fa90-2c84-4452-9eb1-2d975f91d223)
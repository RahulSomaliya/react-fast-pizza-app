# react-fast-pizza-app

This pizza ordering app has a menu fetched from an open-source API, has cart functionality, and has an ordering feature (there is no payment gateway yet). 

The latest feature of React Router i.e. data loading feature for remote state management has been implemented to GET, POST, and basically perform each remote state management. For global state management, I've used Redux with the modern Redux Toolkit way of doing it - This is a big leap from combining reducers with context API to providing global state. Also, I've also experimented with Thunks middleware action dispatching to perform asynchronous actions (used when accessing geoLocation from the user and fetching reverse geoCoding i.e. fetching address from lat, lng). Plus, for the first time, I didn't have to stumble upon - the `what should I name this class` dilemma for this project as I've used Tailwind CSS, and I see it as a very intuitive way of styling basically anything.

Get your *imaginary pizza for free at https://react-fast-pizza-app.vercel.app

context folder: state management tool
to pass data to components
centralize data
context api helps to centralize data and any components can access the data

Login.jsx
-submitHandler: performs two way binding
-e: is used for event listner
-e.preventDefault: will prevent default behavior of form
-useState of email: refers that email will be empty string
-similar for useState of password
-onChange function: activates when change ocuure
-e.target: which element is performing
-e.target.value: what is the value of targeted element
-value={email}: will be empty bcz in useState we have empty string if it had any value it will be displayed
-selEmail ma aba hamle value email wala add garem

-local storage: browser space where we can store small data
-localStorage.clear() to clear local storage
-data in localstorage can be distributed by context api

-useEffect: side stack other than main stack ma function chalaune garcha
-JSON.stringify() converts data into string
-JSON.parse() converts data into array
-localStorage.setItem() to set data in local storage
-localStorage.getItem() to get data from local storage
-find(): array method to find patiular value inside array

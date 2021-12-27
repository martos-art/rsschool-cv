# Martos Artsiom

----
#### Contacts:
* Phone: +375298083145
* Email: martos.artm@gmail.com

----
#### About me:
I study at RS school to be a skilled front-end developer

----
#### Skills:
* HTML, CSS
* JavaScript
* ReactJS
* Git

----
#### Code example:
```javascript
const SET_USER_DATA = 'SET_USER_DATA';

let initialState = {
    userId: null,
    email: null,
    login: null
}

const authReducer = (state = initialState, action) => {
    switch (action.type) {
        case SET_USER_DATA:
            return {
                ...state,
                ...action.data
            }

        default:
            return state;
    }
};
export const setUserData = (userId, email, login) => ({type: SET_USER_DATA, data: {userId, email, login} });

export default authReducer;
```

----
#### Education:
Minsk State Polytechnic College

----
#### Languages:
* English - A1 (working hard to improve it)
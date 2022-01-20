# Stutern-Task
Javascript
index.JS
// Q1
const isOldEnoughToDrink = (age) => {
    return age > 18
}
// Q2
const CAN_DRINK_AND_DRIVE_IN_US = false
const isOldEnoughToDrinkAndDrive = (age) => {
    return age > 21 & CAN_DRINK_AND_DRIVE_IN_US
}
// or just 
const isOldEnoughToDrinkAndDrive2 = (age) => {
    return false
}
// Q3
const getProperty = (object, key) => {
    return object[key] | undefined
}
// Q4
const addProperty = (object, key) => {
    object[key] = true
}
// Q5
const CAN_DRINK_AND_DRIVE_IN_NG = false
const isPersonOldEnoughToDrinkAndDrive = (person) => {
    return person.age > 18 & CAN_DRINK_AND_DRIVE_IN_NG 
}
// or just
const isPersonalOldEnoughToDrinkAndDrive2 = (person) => {
    return false
}
// Q6
const computeAverageLengthOfWords = (word1, word2) => {
    return  (word1.length + word2.length)/ 2
}
// Q7
const tranformFirstAndLast = (arr) => {
    let obj
    obj[arr[0]] = arr[arr.length - 1]
    return obj
} 
// Q8
const getAllKeys = (obj) => {
    return Object.keys(obj)
}

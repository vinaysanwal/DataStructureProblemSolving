Problem 1: Reverse an Array::

Sol1)

function reverseArray(arr){
return reverse(arr)
}

sol2)

function reverseArray(arr){
return arr.map((item , id) => {
   arr[arr.length-1-id]
})
}

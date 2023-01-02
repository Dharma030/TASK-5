// Print odd numbers in an array
let arr = [1, 2, 3, 4, 5, 6, 7, 8, 9];
let odds = arr.filter((number) => {
  return number % 2 !== 0;
});
console.log(odds);

// Convert all the strings to title caps in a string array
function toTitleCase(str) {
  str = str.toLowerCase().split(" ");
  for (var i = 0; i < str.length; i++) {
    str[i] = str[i].charAt(0).toUpperCase() + str[i].slice(1);
  }
  return str.join(" ");
}
console.log(toTitleCase("I AM THE BEST CODER IN THE WORLD"));

// Sum of all numbers in an array
let numbers = [10, 20, 30, 40, 50];
let sum = 0;
for (let i = 0; i < numbers.length; i++) {
  sum += numbers[i];
}
console.log(sum);

// Return all the prime numbers in an array
let num = [-1, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15];
let result = [];
function isPrime(num) {
  if (num < 2) return false;
  for (let i = 2; i < num; i++) {
    if (num % i === 0) {
      return false;
    }
  }
  return true;
}
num.forEach(function (element) {
  const item = isPrime(element);
  if (item) {
    result.push(element);
  }
});
console.log(result);

// Return all the palindromes in an array
str = "DEEPTESH";
function checkPalindrome(str) {
  const len = str.length;

  for (let i = 0; i < len / 2; i++) {
    if (str[i] !== str[len - 1 - i]) {
      return "It is not a palindrome";
    }
  }
  return "It is a palindrome";
}
const value = checkPalindrome(str);
console.log(value);

// Return median of two sorted arrays of the same size.

var ar1 = [1, 12, 15, 26, 38];
var ar2 = [2, 13, 17, 30, 45];
function getMedian(ar1, ar2, n) {
  var i = 0;
  var j = 0;
  var count;
  var m1 = -1,
    m2 = -1;

  for (count = 0; count <= n; count++) {
    if (i === n) {
      m1 = m2;
      m2 = ar2[0];
      break;
    } else if (j === n) {
      m1 = m2;
      m2 = ar1[0];
      break;
    }
    if (ar1[i] <= ar2[j]) {
      m1 = m2;
      m2 = ar1[i];
      i++;
    } else {
      m1 = m2;
      m2 = ar2[j];
      j++;
    }
  }

  return (m1 + m2) / 2;
}

console.log("Median is " + getMedian(ar1, ar2, n1));

// Remove duplicates from an array
let chars = ["A", "B", "A", "C", "B"];

let duplicateChars = [];
chars.forEach((element) => {
  if (!duplicateChars.includes(element)) {
    duplicateChars.push(element);
  }
});

console.log(duplicateChars);

// Rotate an array by k times
function RightRotate(a, n, k) {
  k = k % n;

  for (let i = 0; i < n; i++) {
    if (i < k) {
      document.write(a[n + i - k] + " ");
    } else {
      document.write(a[i - k] + " ");
    }
  }
  document.write("<br>");
}
let Array = [1, 2, 3, 4, 5];
let N = Array.length;
let K = 2;

RightRotate(Array, N, K);

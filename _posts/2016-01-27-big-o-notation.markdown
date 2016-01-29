---
layout: post
title:  "Big O(N^YEAH)"
date:   2016-01-27 13:27:32 -0600
categories: big-o notation
---

In the realm of computer science, Big O notation is a big deal when it comes to designing efficient algorithms. At it's most basic level, Big O is a method for labelling and classifying the amount of iterations an algorithm will need to perform on a dataset in relation to the size of the dataset. Let's take a look at some basic examples of algorithms and give a broad explanation of their respective notations.

O(1) or Order of 1, n is an algorithm that executes in the same amount of time regardless of how big the dataset running through it is. An example of an order of 1 algorithm would be something like adding a new item to an array. Even if you execute this algorithm on a 10,000 item array, it will execute in the same amount of time as any other size array. Here's an example of an Order of 1 algorithm executed in JavaScript.

{% highlight ruby %}
var carTypes = ["Sedan", "Coup", "SUV",];
carTypes.push("Minivan");
{% endhighlight %}


O(N) or Order of N is an algorithm that's execution time is directly proportional to the size of the dataset that it is acting on. This typically refers to an action that needs to iterate through an entire dataset. A common example cited as an Order of N algorithm would be a linear search. This is a type of search function that checks every element of the dataset for matching data and returns a matching index or key. Here's an example of an Order of N linear seach algorithm in JavaScript.

{% highlight ruby%}
var searchTerm = "Search Term"
for( var x = 0; x < array.length; X++ ) {
	if(array[x] == search_term) {
		return x;
	}
}
{% endhighlight %}

O(N^2) or Order of N^2 algorithms are algorithms whose execution times are exponentially proportional to the size of the dataset. Typically when processing algorithms for speed, these are not recommended as they generally require the processor to comb through the entire dataset repeatedly and re-perform a block of code. The insertion sort algorithm is an algorithm that in a lot of cases performs at an O(N^2). This algorithm iterated through data looking for unsorted information and then moving it to the correct spot after iterating back through previous data and moving it to accommodate for new placement of the unsorted information. While lovely to see in action, these algorithms can be inefficient. Here's an example of an insertion algorithm below.

{% highlight ruby %}
 function insertionSort(array) {
     for (var y = 1; j < array.length; j++) {
         var key = array[j];
         var x = y - 1;
         while (i >= 0 && key < list[i])     {
             list[x + 1] = list[x];
             x = i - 1;
         }
         array[i+1] = key;
     }
 }
{% endhighlight %}

O(log N) or Order of Log N algorithms perform in a manner so that the amount of information being used is decreased by half through every iteration of the algorithm. A binary search is a perfect example of this. In a binary search, the middle element of the dataset is selected. Say we have an array - [1, 2, 3, 4, 5, 6, 7] and we want to find the number 3. The middle element is selected in the array, which in this case is 4. Since we know that 3 is less than 4, all of the data that's greater than 4 can be discarded. Now we only have to iterate through half of the data! So now we are left with a smaller set of numbers - 1, 2, 3. The algorithm runs again and it defines the middle element again. This time it's 2. So now we know that 2 is less than 3 so 2 and 1 are removed from the array and we are left with our number! Let's look at a Ruby binary search:

{% highlight ruby %}
def binary_search(term, array)
  midpoint = (array.length - 1) / 2
  if array.length == 0
    return nil
  elsif array.length == 1
    return array.index(term)
  else
    if term > array[midpoint]
      (midpoint + 1) + binary_search(term, array[midpoint+1..-1])
    else
      binary_search(term, array[0..midpoint])
    end
  end
end
#=> returns the index of the 'term' argument
{% endhighlight %}

There are several more common forms that get more in depth as you further dive into the realm of discrete mathematics. This is just a broad overview at the moment. Stay tuned for a more detailed dive into this useful notation.

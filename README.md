# [array-abs]

[array-abs] is a library of vanilla Pd abstractions that manipulate data contained in Pd's built-in [array] object.

## List of objects

* [array-abs-val]: take the absolute value of all elements in an array
* [array-append]: append values to the end of an array (and resize it)
* [array-between]: search for values between specified limits
* [array-bintofreq]: convert all values from FFT bin number to frequency in Hz
* [array-ceil]: round all values up to the next highest integer
* [array-clip]: clip all values within specified limits
* [array-copy]: copy all values from a source array (and resize the target array)
* [array-copy-range]: copy a specified range of values from a source array
* [array-dbtorms]: convert all values from dB to RMS amplitude
* [array-delete]: delete a specified range of values and resize the target array
* [array-drip]: output all values in an array one at a time as quickly as possible
* [array-equals]: search for occurrences of a specific value
* [array-floor]: round all values down to the next lowest integer
* [array-freqtobin]: convert all values from frequency in Hz to FFT bin number
* [array-ftom]: convert all values from frequency in Hz to MIDI note number
* [array-geomean]: compute the geometric mean of an array
* [array-greater]: search for values above a specified threshold
* [array-insert]: insert values at a specified index and resize the target array
* [array-lesser]: search for values below a specified threshold
* [array-maxk]: search for the K largest values in an array
* [array-mean]: compute the arithmetic mean of an array
* [array-median]: compute the median of an array
* [array-mink]: search for the K smallest values in an array
* [array-mode]: compute the mode of an array
* [array-mtof]: convert all values from MIDI note number to frequency in Hz
* [array-nearest]: search for the value in an array nearest to a query value
* [array-offset]: add a value to all elements in an array
* [array-pow]: raise all values to a speficied power
* [array-prepend]: prepend values to the beginning of an array (and resize it)
* [array-rand-fill]: fill an array with random values within a specified range
* [array-random-walk]: fill an array with a random walk with specified parameters
* [array-range]: compute the range of an array
* [array-reverse]: reverse the elements of an array
* [array-rmstodb]: convert all values from RMS to dB amplitude
* [array-round]: round all values to the nearest integer
* [array-scale]: multiply all elements in an array against a specified value
* [array-scramble]: randomize the order of elements in an array
* [array-series]: fill an array with a series
* [array-shift]: shift all elements in an array forwards or backwards (with wraparound)
* [array-shift0]: shift all elements in an array forwards or backwards, leaving zeros in place of shifted elements
* [array-sort]: sort values in ascending or descending order
* [array-std]: compute the standard deviation of an array
* [array-unique]: return a list of all unique values in an array
* [array-window]: fill an array with a specified FFT window function

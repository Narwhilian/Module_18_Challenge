# Simple Blockchain

This python file establishes and validates a blockchain.

---

## Technologies

This project uses the Python Programming language in a python file (.py) as well as the following libraries
    
    - streamlit
    - dataclass
    - List (type)
    - Datetime
    - Pandas
    - Hashlib

---

## Installation Guide

To install you will want to pull the entire Blockchain folder from github
    

    * pychain.py (the python file itself)
    * ReadMe (This file)


---

## How it works

1) First the user will open their terminal (I used git bash) and navigate into the folder containing the pychain.py file
2) Then the user will simply run the file using streamlit by typing in 
```
streamlit run pychain.py
```
    
3) from there it should automatically open a webpage displaying the blockchain ledger with functionality to allow the user to add to that blockchain

I added a handful of new blocks on mine to ensure that the program worked as intended

![Pychain_screenshot](https://user-images.githubusercontent.com/84096312/135733018-1f65f874-d6a9-40b2-ab4a-26d6daa88a10.png)


I also checked the blockchain by using the validate button at the bottom and got the true result, showing that it chained the data correctly

![validated_chain](https://user-images.githubusercontent.com/84096312/135733034-0c0479b6-e56a-41fb-a932-3de8a4d397aa.png)


---

## Usage

Overall it should be a very simple application to use, all you need to do is open the terminal, navigate to where you have stored the pychain.py file and then run the file on streamlit by typing the following line into your terminal
```
streamlit run pychain.py
```
---

## Contributors

Colin Benjamin

Linkedin: [Colin Benjamin](https://www.linkedin.com/in/colinbenjamin/)
    
email: cbenjamin33@gmail.com

---

## License

(c) Copyright 2021 Colin Benjamin

Licensed under the MIT license:

    http://www.opensource.org/licenses/mit-license.php


Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

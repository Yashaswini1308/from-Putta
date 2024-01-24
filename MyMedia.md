## Sai Shivani Yashaswini Putta

"Half Girlfriend" is a novel written by Indian author Chetan Bhagat,The book was published in 2014 and quickly gained popularity in India.The novel was later adapted into a Bollywood film with the same name.

![Image](https://github.com/Yashaswini1308/from-Putta/assets/156264564/36444236-89b4-45fb-8486-fb024a77e4c4)

---

### Recommended Books

The table below shows reccmmendations for books

|Name          |Reason                    |Creator Name        |
|:-------------|:-------------------------|:-------------------|
|My Experiments with Truth|Its an autobiography and describing struggle for India's independence|Mahatma Gandhi|
|2 States|A love story about a couple from different states in India, dealing with the complexities|Chetan Bhagat|
|The Inheritance of Loss|A novel that intertwines the stories of characters in India and the United States, addressing themes of identity and the impact of globalization|Kiran Desai|
|The White Tiger|A darkly humorous and thought-provoking novel|Aravind Adiga|

---

### Favorite Quotes
>You have within you right now, everything you need to deal with whatever the world can throw at you - *Vikas swarup*
>
>Your time is limited, don't waste it living someone else's life - *steve jobs*

---
### Code Fencing

How to use Python to merge list of lists

~~~
def merge(*args, missing_val = None):
  max_length = max([len(lst) for lst in args])
  out_list = []

  for i in range(max_length):
    out_list.append([args[k][i] if i < len(args[k]) else missing_val for k in range(len(args))])

  return out_list
~~~
> https://stackoverflow.com/questions/716477/join-list-of-lists-in-python
> Quick link for code snippet: https://code.pieces.app/collections/python
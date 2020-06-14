<!-- Game of Thrones : Houses And People"s Name -->
<!-- Try to first understand how Array in Objects & Objects in Array are arranged in this example.
    Only when you don't get it by yourself, comeback again and read the hint -->
    <!-- Hint:
            got is an Object which has one key: `houses`.
            `houses` is an array of house(here two house in houses).
            Each house is an Object which has two keys: "name" and "people".
            "people" is an array of all persons living in that particular house.
            And, each person is an array with keys: "name" and "description"
     -->
    



const got = {
  houses: [
    {
      name: "Starks",
      people: [
        {
          name: "Eddard Stark",
          description:
            "Lord of Winterfell - Warden of the North - Hand of the King - Married to Catelyn (Tully) Stark",
        },
        {
          name: "Benjen Stark",
          description:
            "Brother of Eddard Stark - First ranger of the Night's Watch",
        },
        {
          name: "Robb Stark",
          description: "Son of Eddard and Catelyn Stark - Direwolf: Grey Wind",
        },
        {
          name: "Sansa Stark",
          description: "Daughter of Eddard and Catelyn Stark - Direwolf: Lady",
        },
        {
          name: "Arya Stark",
          description:
            "Daughter of Eddard and Catelyn Stark - Direwolf: Nymeria",
        },
        {
          name: "Brandon Stark",
          description: "Son of Eddard and Catelyn Stark - Direwolf: Summer",
        },
        {
          name: "Rickon Stark Upper",
          description: "Son of Eddard and Catelyn Stark - Direwolf: Shaggydog",
        },
        {
          name: "Jon Snow",
          description:
            "Bastard son of Eddard Stark - Steweard in the Night's Watch - Direwolf: Ghost",
        }
      ]
    },
    {
      name: "Lannisters",
      people: [
        {
          name: "Tywin Lannister",
          description: "Lord of Casterly Rock - Warden of the West",
        },
        {
          name: "Tyrion Lannister",
          description: "Son of Tywin Lannister - The Imp",
        },
        {
          name: "Jaime Lannister",
          description:
            "The Kingslayer - Knight of the Kingsgaurd - Son of Tywin Lannister",
        },
        {
          name: "Cersei Baratheon",
          description:
            "Married to King Robert Baratheon - Daughter of Tywin Lannister",
        }
      ]
    }
  ]
}


<!-- questions -->
Write codes for the following problems along with its output.
1. print the value of key "houses"/print the length of array "houses"
2. Print the name of all houses in got.
3. Push the name of the houses in an array and print the array.
3. Get list of people living in each house of got
4. Find the number of people living in each house of got
5. push the length of the people of each house into an array and console it
6. print name of all persons living in both house(print name of persons of both house altogether)
7. push all names into an array and print the array.
8. print descritption of all persons living in both house(print description of persons of both house altogether)
9. push all descriptions into an array and print the array.
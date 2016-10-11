## Development: Week 3
![alt text](https://s-media-cache-ak0.pinimg.com/564x/c3/3f/fa/c33ffac80ec16553ec8694b6b4617667.jpg "Unicorn")
### Dit is een eenhoorn.

#### Javascript

* Infinity om oneindigheden te voorkomen (Vastlopen)

* Oefening:
    * // Object constructor notation
      function Person() {
        this.firstName;
        this.surName;
        this.isFemale;
        this.toString = function() {
          return this.firstName + ' ' + this.surName;
        }
      }

      // Create a new person --> make an instance
      var p1 = new Person;
      p1.firstName = "Donald";
      p1.surName = "Muyle";
      p1.isFemale = false;
      console.log(p1.toString());
      p1.firstName = "Lode";
      console.log(p1.toString());

* Oefening2:
    *// Object constructor notation
     function Movie() {
       this.movieName;
       this.movieYear;
       this.movieGenre;
       this.toString = function() {
         return 'Name: '+ this.movieName + '\n' + 'Year: ' + this.movieYear + '\n' + 'Genre: ' + this.movieGenre   }
     }

     // Create a new Movie --> make an instance
     var m1 = new Movie;
     m1.movieName = "Melker Lode";
     m1.movieYear = "1969";
     m1.movieGenre = "Horror";

     console.log(m1.toString());

     m1.movieGenre = "Horror/Drama";

     console.log(m1.toString());



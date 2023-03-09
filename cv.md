
Curriculum Vitae

Personal Information:

  Name: Oleh Poiasnik

  Email: opoiasnik@gmail.com

  Education:
  Technical university of Kosice

  Field of Study: Programming


  Achievements: 
Developed skills in programming (doing projects)

Skills: Programming languages: 

  •	JavaScript (base level)

  •	C

  •	HTML/CSS

Languages:

  •	English (intermidiate)

  •	Russian (native)

  •	Ukrainian (native)

Hobbies and Interests:

  •	Reading books on programming languages

  •	Playing some “Brain games”

  •	Writing code

Example of code:

    function duplicateEncode(word) {
      const letters = word.toLowerCase().split('');
      let result = '';

      for (let i = 0; i < letters.length; i++) {
        const char = letters[i];
        if (letters.indexOf(char) === letters.lastIndexOf(char)) {
          result += '(';
        } else {
          result += ')';
        }
      }
      return result;
    }


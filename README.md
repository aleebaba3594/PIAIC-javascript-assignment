1)    node.js and vs studio installed

2)  	let a = "Eric";
    	console.log("Hello",a,",would to like to learn some python todays!");

3)   	let faseeh = "Faseeh ur rehman";
    	let lowercase = faseeh.toLocaleLowerCase();
    	let uppercase = faseeh.toLocaleUpperCase();
    	let titlecase = faseeh
      	.split(" ")
      	.map((ele) => {
        return ele.replace(ele[0], ele[0].toUpperCase());
      	})
      	.join(" ");
    	console.log(
      	`  ${titlecase},
      	"title case",
      	${lowercase},
      	"lower case",
      	${uppercase},
      	"upper case"
    	`
    	);

4)   	console.log(`Ertugrul ghazi said "Only those who dream big can walk forward in the road of victory".`);

5)     	let famous_person = "Ertugrul Ghazi";
    	let message = `"One who has no dreams, has no future."`;
    	console.log(famous_person, "said", message);

6)      let person_name = "\t\t\t\t\t" + "Faseeh" + "\t\t\t\t\t";
    	let remove_whitespace = person_name.trim();
    	console.log(person_name, "\n", remove_whitespace);

7)  	console.log(2 * 4);
    	console.log(4 + 4);
    	console.log(9 - 1);
    	console.log(64 / 8);
      
8)    console.log(2 * 4);
    	console.log(4 + 4);
    	console.log(9 - 1);
    	console.log(64 / 8);
      
      
9) 	let fav_number = 3;
    	console.log(fav_number, " is my lucky number");

10) 	let famous_person = "Ertugrul Ghazi";
    	let message = `"One who has no dreams, has no future."`;
    	let comment = "Etrugrul Ghazi quotes";
    	console.log(
      	famous_person,
      	"said",
      	message,
      	"\n",
      	"comment :",
      	comment,

      	"\n",

      	"This program prints the message"
    	);

    	let person_name = "\xa0\xa0\xa0" + "Faseeh" + "\xa0\xa0\xa0";
    	let remove_whitespace = person_name.trim();
    	let coment = "Removing white spaces";
    	console.log(
      	remove_whitespace,
      	"\n",
      	"comment :",
      	coment,
      	"\n",
      	"this program remove the white spaces"
    	);

11)	let names = ["Ali", "Bilal", "Faseeh", "Rizwan"];
    	names.map((ele) => {
      	console.log(ele);
    	});

12)   	let names = ["Ali", "Bilal", "Faseeh", "Rizwan"];
    	names.map((ele) => {
      	console.log(ele, "is my class fellow and my best friend.");
    	});

13) 	let names = ["Honda_Civic", "Land_cruiser", "Mercedes", "Lamborghini"];
    	console.log(`${names[0]} "I want to buy Honda Civic"`);
    	console.log(
      	`${names[1]} "the cops don't think about stopping you so much"`
    	);
    	console.log(
      	`${names[2]}
      	" If you want something don’t just wish for it. Life is too short to wait. "`
    	);
    	console.log(
      	`${names[3]}
      	"Work Until your car’s Door opens in a vertical way!"`
    	);

14)  	let guests = ["Faseeh", "Ali", "Bilal"];
    	guests.forEach((ele) => {
      	console.log(ele, "you are invited on dinner");
    	});

15)    	let guests = ["Faseeh", "Ali", "Bilal"];
    	guests.forEach((ele) => {
      	console.log(ele, "you are invited on dinner");
    	});
    	console.log("Bilal can’t make the dinner");
    	let new_list = guests.pop();
    	let new_guest = "Ahmed";
    	let check_list = guests.push(new_guest);
    	console.log(guests);
    	guests.map((ele) => {
      	console.log(ele, "you are invited");
    	});

16) 	let guests = ["Faseeh", "Ali", "Bilal"];
    	sending_invitaion();
    	console.log("Bilal can’t make the dinner");
    	let new_list = guests.pop();
    	let new_guest = "Ahmed";
    	let check_list = guests.push(new_guest);
    	console.log(guests);
    	sending_invitaion();

    	console.log("We have a big dinner tonight ");
    	guests.unshift("Rizwan");
    	guests.splice(2, "", "Saif");
    	guests.push("Hasnain");
    	console.log(guests);
    	sending_invitaion();

    	function sending_invitaion() {
      	guests.forEach((ele) => {
        console.log(ele, "you are invited on dinner");
      	});
    	}

17)    	let guests = ["Faseeh", "Ali", "Bilal"];
    	sending_invitaion();
    	console.log("Bilal can’t make the dinner");
    	let new_list = guests.pop();
    	let new_guest = "Ahmed";
    	let check_list = guests.push(new_guest);
    	console.log(guests);
    	sending_invitaion();

    	console.log("We have a big dinner tonight ");
    	guests.unshift("Rizwan");
    	guests.splice(2, "", "Saif");
    	guests.push("Hasnain");
    	console.log(guests);
    	sending_invitaion();

    	function sending_invitaion() {
      	guests.forEach((ele) => {
        console.log(ele, "you are invited on dinner");
      	});
    	}
    	console.log("only two person dinner are availabe");
    	let removing1 = guests.pop();
    	console.log(removing1, "i am sorry , i can't inivite to dinner");
    	let removing2 = guests.pop();
    	console.log(removing2, "i am sorry , i can't inivite to dinner");
    	let removing3 = guests.pop();
    	console.log(removing3, "i am sorry , i can't inivite to dinner");
    	let removing4 = guests.pop();
    	console.log(removing4, "i am sorry , i can't inivite to dinner");
    	sending_invitaion();
    	console.log((guests.length = []));


18)   	let arr = ["Japan", "Iran", "Turkey", "America", "Switzerland"];
    	const sorted = [...arr].sort();
    	console.log(arr, "arr in its original order");
    	console.log(sorted, "after sorting the arr");
    	console.log(arr, "the pervious arrays did not change ");
    	let previous_arr = sorted.reverse();
    	console.log(previous_arr, "Reverse alphabetic order");
    	console.log(arr, "the arr is still not changed");
    	let sec_rev = arr.reverse();
    	console.log(sec_rev, "changing the order in reverse");
    	let again_rev = sec_rev.reverse();
    	console.log(
      	again_rev,
      	"again reverse the order to make it in  original arr format"
    	);
    	let sorting = again_rev.sort();
    	console.log(
      	sorting,
      	"now it is in alphabetic order after sorting the array"
    	);
    	let rev_last = sorting.reverse();
    	console.log(rev_last, "arr is in reverse alphabetic order")

19)	let guests = ["Faseeh", "Ali", "Bilal"];
    	console.log(guests.length, " guests are invited on dinner");

20)   	let countries = [
      	"Pakistan",
      	"Saudia-Arabia",
      	"Africa",
      	"India",
      	"America",
      	"England",
      	"France",
      	"Switzerland",
      	"Bangladesh",
      	"Turkey",
      	"Iran",
      	"Iraq",
      	"Afghanistan",
      	"Canada",
      	"Australia",
      	"Japan",
      	"Antarctica",
      	"Argentina",
      	"Russia",
      	"Belgium",
    	];

21)  	let a = prompt("enter the name");
    	let b = prompt("enter the age");
    	function Obj(name, age) {
      	console.log({ name, age });
   	}
    	Obj(a, b);

22)	let names = ["Honda_Civic", "Land_cruiser", "Mercedes", "Lamborghini"];
    	// i have changes the index so it cannot acccess it
    	// console.log(`${names[6]} "I want to buy Honda Civic"`);
    	console.log(`${names[0]} "I want to buy Honda Civic"`);
    	console.log(
      	`${names[1]} "the cops don't think about stopping you so much"`
    	);
    	console.log(
      	`${names[2]}
      	" If you want something don’t just wish for it. Life is too short to wait. "`
    	);
    	console.log(
      	`${names[3]}
      	"Work Until your car’s Door opens in a vertical way!"`
    	);

23)  	let car = "mehran";
    	console.log("Is car == 'mehran'? I predict True.");
    	console.log(car == "mehran");

    	let bike = "honda";
    	console.log("Is car == 'honda125'? I predict False.");
    	console.log(car == "honda125");

    	let cycle = "civic";
    	console.log("Is car == 'civic'? I predict True.");
    	console.log(cycle == "civic");

    	let moto = "v8";
    	console.log("Is car == 'v86'? I predict False.");
    	console.log(car == "v86");


    	let age = 15;
    	console.log("Is age == 15? I predict True.");
    	console.log(age == 15);


24)   	let car = "mehran";
    	console.log(car == "mehran", "if car is equal to mehran");
    	console.log(car != "mehran", "if car is not equal to mehran");

    	let bike = "Honda";
    	console.log(bike == "Honda", "if bike is equal to Honda");
    	console.log(bike.toLowerCase() == "Honda", "if bike is not equal to Honda");

    	let age = 15;
    	console.log(age == 15, "if age is equal to given age");
    	console.log(age != 15, "if age is not equal to given age");
    	console.log(age > 10, "if age is greater than  given age");
    	console.log(age < 15), "if age is less than  given age";
    	console.log(
      	age >= 15,
      	"if age is greater than and equal to that given age"
    	);
    	console.log(age <= 13, "if age is less than and equal to that given age");

    	console.log(
      	age == 15 || bike == "Honda",
      	"if both statement are right then it is true"
    	);
    	console.log(
      	age == 15 && bike != "Honda",
      	"if both statement are not right then it is false"
    	);
    	console.log(typeof car != [], "the type of car is not a array");
    	console.log(typeof car == [], "dont have an array");

25) 	let val= prompt("enter the color")
	let alien_color = val
	if(alien_color == "green"){ console.log("the player just earned 5 points for shooting the alien.")}

26)	let val= prompt("enter the color")
	let alien_color = val
	alien_color == "green"? console.log("the player just earned 5 points for shooting the alien."): console.log("the player just earned 10 points.")

27)	let alien_color= prompt("enter the color").toLowerCase()
	if(alien_color=="green"){
    	console.log("the player earned 5 points")
	} 
	if(alien_color=="yellow"){
    	console.log("the player earned 10 points")
	} 
	if(alien_color=="red"){
    	console.log("the player earned 15 points")
	}

28)	let age = 40
	if(age<2){
    	console.log("the person is a baby")
	} 
	if(age>=2 && age<4){
    	console.log("the person is a toddler")
	} 
	if(age>=4 && age<13){
    	console.log("the person is a kid")
	} 
	if(age>=13 && age<20){
    	console.log("the person is a teenager")
	} 
	if(age>=20 && age<65){
    	console.log("the person is a adult")
	} 
	if(age>=65){
    	console.log("the person is a elder")
	}

29)   	let fruits=["apple","orange","banana","peach","guava"]
	let favoriteFruits=["apple","orange","banana"]
	if(favoriteFruits.includes("apple")){
    	console.log("I really like apple")
	}
	if(favoriteFruits.includes("orange")){
    	console.log("I really like orange")
	}
	if(favoriteFruits.includes("banana")){
    	console.log("I really like banana")
	}
	if(favoriteFruits.includes("peach")){
    	console.log("I really like peach")
	}
	if(favoriteFruits.includes("guava")){
    	console.log("I really like guava")
	}

30) 	let user=["admin","ali","faseeh","rizwan","khan"]
	user.forEach((ele)=>{
    	if(ele=="admin"){
        console.log("Hello",ele,",would you like to see a status report?")
    	}
    	else{
        console.log("Hello",ele,", thank you for logging in again.")
    	}
	})

31)	let user=["admin","ali","faseeh","rizwan","khan"]
	if(user.length>0){
    	user.length==[]
    	console.log("We need to find some users!")
	}

32) 	let current_users=["asad","ali","Faseeh","rizwan","khan"]
	let new_users=["rizwan","gunjan","khan","hafeez","faseeh"]
	new_users.forEach((ele)=>{
    	if(current_users.includes(ele)){
       	ele.toLowerCase() 
        console.log(ele," is already taken")
    	}
    	else{
           console.log(ele," is available")
    	}
  	
	}
        )

33)	let ordinalNumbers=[1,2,3,4,5,6,7,8,9]
	ordinalNumbers.forEach((ele)=>{
    	if(ele===1){
        console.log(ele + "st")
    	}
     	if(ele===2){
        console.log(ele + "nd")
    	}
     	if(ele===3){
        console.log(ele + "rd")
    	}
   	if(ele>3 && ele<10){
        console.log(ele + "th")
    	}
	})

34)	let favoritePizza=["Fajita","Tika","Lazania"]
	favoritePizza.forEach((ele)=>{
    	console.log("I like",ele,"pizza")
	})
	console.log(`i like all kind of pizzas\nspecially :\nTika\nFajita\nLazania\nIn short I love Pizzas`)

35)	let animals=["pink panther","lion","leopard"]
	for(i=0; i<animals.length ; i++){
    	if(animals[i]==="pink panther"){
    	console.log(animals[i],"is a great pet")
    	}
     	if(animals[i]==="lion"){
    	console.log(animals[i],"is also a great pet")
    	}
     	if(animals[i]==="leopard"){
    	console.log(animals[i],"is a beast pet")
    	}
	}
  	console.log("Any of these animals would make a great pet!")

36)    	function make_Tshirt(size, message) {
      	console.log("the shirt size is large", size, "\n", "message:", message);
    	}
    	make_Tshirt(15, "never give up");

37)  	let default_mxg = "I love javascript";
    	let a = prompt("enter the size large medium or small");
    	let b = prompt("enter the message you want on that t-shirt");
    	function make_Tshirt(size, message) {
      	if (size == "large" || size == "medium") {
        console.log(size, default_mxg);
      	} else {
        console.log(`this size is for kids "${size}" \n "message:" ${message}`);
     	}
    	}
    	make_Tshirt(a, b);

38)  	let country = "Pakistan";
    	let a = "Lahore";
    	let b = "Karachi";
    	let c = "Mumbai";
    	function describe_city(a, b, c) {
      	console.log(
        a,
        "is in Pakistan",
        "\n",
        b,
        "is in Pakistan",
        "\n",
        c,
        "is not in Pakistan"
      	);
    	}
    	describe_city(a, b, c);

39)     function city_country(city, country) {
      	return console.log(`"${city}, ${country}"`);
    	}
    	city_country("Lahore", "Pakistan");
    	city_country("Mumbai", "India");
    	city_country("London", "England");

40)     function make_album(artist_name, album_title, track = 0) {
      	console.log({ artist_name, album_title, track });
    	}
    	make_album("faseeh", "javascript");
    	make_album("ali", "python");
    	make_album("rizwan", "java");
    	make_album("bilal", "node", "15");

41) 	let magicians_name = ["ali", "faseeh", "bilal"];
    	function show_magicians(magicians_name) {
      	magicians_name.map((ele) => {
        console.log(ele);
      	});
    	}
    	show_magicians(magicians_name);

42)	let magicians_name = ["ali", "faseeh", "bilal"];
    	function show_magicians(magicians_name, message) {
      	magicians_name.map((ele) => {
        console.log(ele, message);
      	});
    	}
    	show_magicians(magicians_name, "the great_magicians");


43) 	let magicians_name = ["ali", "faseeh", "bilal"];
    	function show_magicians(magicians_name, message) {
      	magicians_name.map((ele) => {
       	let new_arr = [...ele].join("");
        console.log(new_arr, message);
      	});
    	}
    	show_magicians(magicians_name);
    	show_magicians(magicians_name, "the great_magicians");

44)	function make_sandwich(...items) {
  	console.log("\nI'll make you a great sandwich:");

  	for (var item, a = 0, b = items, c = b.length; a < c; a += 1) {
    	item = b[a];
    	console.log("adding " + item + " to your sandwich.");
  	}

  	console.log("Your sandwich is ready!");
	}

	make_sandwich("roast beef", "cheddar cheese", "lettuce", "honey dijon");
	make_sandwich("turkey", "apple slices", "honey mustard");
	make_sandwich("peanut butter", "strawberry jam");

45) 	function cars(manufacturer_name, modal_name, color, features) {
       	features = features || "Normal";
      	console.log({ manufacturer_name, modal_name, color, features });
    	}
    	cars("James_bond", "Lambarghini", "black", "High_speed");

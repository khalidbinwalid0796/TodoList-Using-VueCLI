1. input field a value dile array te object hisabe push hobe.

2. todolist show hobe pase sob gulo item ar jonno 1ta kore delete button thakbe delte ar jonno & double click a edit ar jonno input field open hobe, esc button click korle edit cancel hobe, edit kore enter press korle value edit hobe, empty string die enter korle ager value show hobe.

3. 1ta button a click korle niche input field open hoy actually edit somoy aita hoy; edit ar input field normally show korbe na, double click korle show korbe; condition button ar somoy true hobe input field ar somoy false hobe r initially false thakbe edit property ta; edit ar method() gulo te object mane todo pass kore dite hobe.

4. completed property initially false but checkbox select korara sathe sathe true hoye jabe; tahole remaining length hobe jgulor completed property false seigulor.

5. <button :class="{ active: filter == 'all' }" @click="filter = 'all'">All</button> aikhane active holo css ar class r aita tokhon ee active hobe jokhon filter ar value all assign hobe, and @click="filter = 'all'"; aita mane holo jokhon all tokhon filter property te all assign hobe, jokhon active tokhon filter a active assign hobe, completed ar somoy filter a completed assign hobe.

6. Conditionally class bind with object
	<input type="checkbox" v-model="todo.completed"> checkbox select korar sathe sathe v-model="todo.completed" ar 
													value true hoye jasse
    <div :class="{ completed : todo.completed }">{{ todo.title }}</div> 

    data ar vitore completed property ase sete kintu false; { completed : todo.completed } aikhane 1st ta holo property name & 2nd ta holo property ar value

7. :class="{'active' : activeLink == 'link'}" -->'active' ata kintu css property
	data ar vitore activeLink : 'link1' kore dea


usage of basic tools
    <input type="text" v-model="message">
    <p>{{ message }}</p>
    <img v-bind:src="imageSrc">
    
    <p v-if="showMessage">Hello Vue!</p>
    <p v-else>Goodbye Vue!</p>

    <li v-for="item in items" :key="item.id">{{ item.text }}</li>

    <button v-on:click="showMsg = !showMsg">show/hide</button>
    <p v-show="showMsg">Hello world</p>





    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin git@github.com:BlackJackChenn/MyNotes.git
    git push -u origin main



<template src ='./tribute.component.html'></template>
<style src='./tribute.component.css'></style>

<script>
export default {
    name: 'Tribute',
    data() {
        return {
            title: 'Dollan',
            subTitle: 'Full Stack Wix Developer',
            figure: {
                src: 'https://www.allentowngroup.com/dollanisms/img/D16.png',
                caption: 'Do you have any code to show?  NOPE!'
            }, 
            timeLine: {
                heading: 'Just a small sample of Dollan and his acheivements',
                events: [
                { id: 0, year: 1987, description: 'The world rejoices as Dollan is born. It is said he came out with a glowing gold halo and Wixxx back tat at birth.' },
                { id: 1, year: 1990, description: 'Dollan has a gift for languages. At age 3 he has learned English, Wixxx, and the newly creating and hot slang based language Dlan.' },
                { id: 2, year: 1995, description: 'The world mournes as Dollan vanishes from the public eye. His followers start to fear the worst.'},
                { id: 3, year: 2000, description: 'Dollan returns and the world breaths a sigh of relief. When asked why the five year disapperance Dollan simply says "legal reasons" and never answers another question about it.'}, 
                { id: 4, year: 2010, description: 'Dollan gets investigated for the 4th time by the IRS to which Dollan says, "I dare a man to try and take my chedder and bread"'},
                { id: 5, year: 2020, description: 'Your saying 2020? It is 2018 how can you predict the future. Dollan responds, "when your coding in Wixxx its like coding in the future. **mic drop**"'}
                ]},
            quote: {
                text: "It's only fun when Dollan don't code none!",
                author: 'Dollan'
            }
        }
    }
}
</script>

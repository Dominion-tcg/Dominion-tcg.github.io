# Dominion: collectable card game deck builder

function init() {
     Tabletop.init( { key: ‘https://docs.google.com/spreadsheets/d/1Wxv5SnuIPoyA_7_JtK4tahVDhMaaJqiqKpvV-SYWOlA/edit#gid=0',
     callback: function(data, tabletop) { 
     console.log(data)
     },
     simpleSheet: true } )
}
window.addEventListener(‘DOMContentLoaded’, init)

## Copyright Information

# Repition Lists, Tables, Forms, Box Models

CTRL + #  does comment out the whole line

## Tables

Tables kinda stink, so does everything else I do not understand completely.
Here is an example of a table with borders, some spans and nth child pseudoclass (bg):<br>
```
<section>
    <h1>Holy Guacamole</h1>
</section>

<table>
    <caption>Tabellenbeschreibung</caption>
    <thead><th>Head</th><th>Head</th><th>Head</th></thead>
    
    <tbody>
        <tr>
            <td>Inhalt </td>
            <td colspan="2">Inhalt </td>
            <!-- <td>Inhalt </td> -->
        </tr>
        <tr>
            <td>Inhalt </td>
            <td>Inhalt </td>
            <td rowspan="2">Inhalt </td>
        </tr>
        <tr>
            <td>Inhalt </td>
            <td>Inhalt </td>
            <!-- <td>Inhalt </td> -->
        </tr>
    </tbody>
    <tfoot><th>Foot</th><th>Foot</th><th>Foot</th></tfoot>
</table>
```
--------------------------

## Forms

**INPUT UN DATTRIBUTMÖGLICHKEITEN**<br>
ein einfaches Eingabefeld für 
* ```Texttype="text"```
defines text input 
<br>

* ```Textname="inputext" ```
name of the inputtext is how the server will find the data


* ```type="password"``` - hidden input

* ```max-length``` - max character length
* ```<buttontype="submit">Abschicken</button>```sends data of the form
* ```type="reset"``` resets form
* ```type="button"``` doesn't do shit on its own

**Labels**<br>
```for``` attribute is used to "marry" labels with (button)IDs (i.e. nice for clicking text and jumping to the correlating input field)


**Placeholder**<br>
```<inputname="myEntry" placeholder="enter placeholder text">```

**Post and Get**<br>
```Post``` is used to send form data hidden, as ```get``` gives away information in the addressline

**Buttons**<br>
There are submit, reset and button, button-types.<br>
There is also an option to create RADIOBUTTONS, which only allow a single choice, CHECKBOXES for multiple choises and SELECTIONBOXES for single or multiple, but with a distinct appearence.<br>
The ```checked``` attribute makes a preselection for radio and checkboxes.

**Textarea**<br>
```<textareaname="kommentar" cols="50" rows="5">Der Wert der Textarea</textarea>```

oh and there is input validation. I surely will get a hold of its meaning and use somewhen too
# UltimateHelper.SQL
This project was created so that DataJuggler.UltimateHelper did not have a dependency on SQL Client.

For use:

using DataJuggler.UltimateHelper.SQL;

Create up to 4 parameters name / value combinations

// create a single parameter array list
string[] parameters = SQLParameterHelper.CreateSQLParameters(parameter1Name, parameter1Value);

// Create two
string[] parameters = SQLParameterHelper.CreateSQLParameters(parameter1Name, parameter1Value, 
    parameter2Name, parameter2Value);

// Create three
string[] parameters = SQLParameterHelper.CreateSQLParameters(parameter1Name, parameter1Value, 
    parameter2Name, parameter2Value, parameter3Name, parameter3Value);

// Create four
string[] parameters = SQLParameterHelper.CreateSQLParameters(parameter1Name, parameter1Value, 
    parameter2Name, parameter2Value, parameter3Name, parameter3Value, parameter4Name, parameter4Value);


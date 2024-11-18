
#include <iostream>
#include <string>
using namespace std;


int main()
{
    // VVVVVVVVVVVVVVVVVVVVV          CODIGO HECHO POR WALTER J. MATOS LOPEZ              VVVVVVVVVVVVVVVV

    string contact1, contact2, contact3, contact4, contact5, contact6, contact7, contact8, contact9, contact10; //estas variables son usadas al inicio del programa, se pueden cambiar a las ya existentes pero habria que cambiar las variables de la parte de informacion
    string date1, date2, date3, date4, date5, date6, date7, date8, date9, date10;
    string link1, link2, link3, link4, link5, link6, link7, link8, link9, link10;
    string note1, note2, note3, note4, note5, note6, note7, note8, note9, note10;
    string ubi1, ubi2, ubi3, ubi4, ubi5, ubi6, ubi7, ubi8, ubi9, ubi10;
    // Todas esas variables se utilizan para almacenar la informacion. De aqui mismo es que se saca la informacion que el usuario ha guardado.
    //Primero, el usuario guardara su informacion deseada en la categoria que decida
    int select;
    cout << "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~\n";
    cout << "Que informacion te gustaria guardar? Porfavor evite utilizar espacios al almacenar.\n";
    cout << "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~\n";
    cout << "1 - Contactos \n";
    cout << "2 - Fechas \n";
    cout << "3 - Links \n";
    cout << "4 - Notes \n";
    cout << "5 - Ubicaciones \n";
    cout << "6 - Finalizar \n";
    cout << "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~\n";
    cout << "Eliga que desea ver:  ";
    cin >> select;
    cout << "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~\n";

    switch (select) {
    case 1:
        cout << "Porfavor escriba el primer contacto que deses guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> contact1;
        cout << "Porfavor escriba el segundo contacto que deses guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> contact2;
        cout << "Porfavor escriba el tercer contacto que deses guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> contact3;
        cout << "Porfavor escriba el cuarto contacto que deses guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> contact4;
        cout << "Porfavor escriba el quinto contacto que deses guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> contact5;
        cout << "Porfavor escriba el sexto contacto que deses guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> contact6;
        cout << "Porfavor escriba el septimo contacto que deses guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> contact7;
        cout << "Porfavor escriba el octavo contacto que deses guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> contact8;
        cout << "Porfavor escriba el noveno contacto que deses guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> contact9;
        cout << "Porfavor escriba el decimo contacto que deses guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> contact10;
        break;
    }
    switch (select) {
    case 2:
        cout << "Porfavor entre la primera fecha que va a guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> date1;
        cout << "Porfavor entre la segunda fecha que va a guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> date2;
        cout << "Porfavor entre la tercera fecha que va a guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> date3;
        cout << "Porfavor entre la cuarta fecha que va a guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> date4;
        cout << "Porfavor entre la quinta fecha que va a guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> date5;
        cout << "Porfavor entre la sexta fecha que va a guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> date6;
        cout << "Porfavor entre la septima fecha que va a guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> date7;
        cout << "Porfavor entre la octava fecha que va a guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> date8;
        cout << "Porfavor entre la novena fecha que va a guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> date9;
        cout << "Porfavor entre la decima fecha que va a guardar. Si no desea guardar mas, dejelo en blanco. ";
        cin >> date10;
        break;
    }
    switch (select) {
    case 3:
        cout << "Entre el primer link que desea guardar. Si termino de guardar, deje el espacio en blanco.";
        cin >> link1;
        cout << "Entre el segundo link que desea guardar. Si termino de guardar, deje el espacio en blanco.";
        cin >> link2;
        cout << "Entre el tercer link que desea guardar. Si termino de guardar, deje el espacio en blanco.";
        cin >> link3;
        cout << "Entre el cuarto link que desea guardar. Si termino de guardar, deje el espacio en blanco.";
        cin >> link4;
        cout << "Entre el quinto link que desea guardar. Si termino de guardar, deje el espacio en blanco.";
        cin >> link5;
        cout << "Entre el sexto link que desea guardar. Si termino de guardar, deje el espacio en blanco.";
        cin >> link6;
        cout << "Entre el septimo link que desea guardar. Si termino de guardar, deje el espacio en blanco.";
        cin >> link7;
        cout << "Entre el octavo link que desea guardar. Si termino de guardar, deje el espacio en blanco.";
        cin >> link8;
        cout << "Entre el noveno link que desea guardar. Si termino de guardar, deje el espacio en blanco.";
        cin >> link9;
        cout << "Entre el decimo link que desea guardar. Si termino de guardar, deje el espacio en blanco.";
        cin >> link10;
        break;
    }

    switch (select) {
    case 4:
        cout << "Escriba el primer note que te gustaria guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> note1;
        cout << "Escriba el segundo note que te gustaria guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> note2;
        cout << "Escriba el tercer note que te gustaria guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> note3;
        cout << "Escriba el cuarto note que te gustaria guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> note4;
        cout << "Escriba el quinto note que te gustaria guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> note5;
        cout << "Escriba el sexto note que te gustaria guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> note6;
        cout << "Escriba el septimo note que te gustaria guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> note7;
        cout << "Escriba el octavo note que te gustaria guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> note8;
        cout << "Escriba el noveno note que te gustaria guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> note9;
        cout << "Escriba el decimo note que te gustaria guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> note10;
        break;
    }
    switch (select) {
    case 5:
        cout << "Escriba la ubicacion que va a guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> ubi1;
        cout << "Escriba la segunda ubicacion que va a guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> ubi2;
        cout << "Escriba la tercera ubicacion que va a guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> ubi3;
        cout << "Escriba la cuarta ubicacion que va a guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> ubi4;
        cout << "Escriba la quinta ubicacion que va a guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> ubi5;
        cout << "Escriba la sexta ubicacion que va a guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> ubi6;
        cout << "Escriba la septima ubicacion que va a guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> ubi7;
        cout << "Escriba la octava ubicacion que va a guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> ubi8;
        cout << "Escriba la novena ubicacion que va a guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> ubi9;
        cout << "Escriba la decima ubicacion que va a guardar. Si no desea guardar mas, deje el espacio en blanco.";
        cin >> ubi10;
    }

    switch (select) {
    case 6:
        cout << "El programa a finalizado, gracias por utilizar. \n"; //finaliza el programa
        break;
    }

    // Estos finalizaran el programa si el usuario no escoge una de las opciones en pantalla.
    if (select > 6) {
        cout << "Input invalido. Escoga una de las opciones presentadas en pantalla. \n";
    }
    else if (select == 0) {
        cout << "Input invalido. Escoga una de las opciones en pantalla.";
    }
    else if (select < 0) {
        cout << "input invalido. Porfavor escoga una de las opciones en pantalla \n";
    }

        // Luego el usuario va a sacar su informacion guardada en esta parte utilizando las variables anteriores.
        // Parte de sacar informacion empieza aqui VVVVVV
        int choice;
        cout << "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~\n";
        cout << "Que informacion guardada te gustaria sacar? \n";
        cout << "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~\n";
        cout << "1 - Contactos \n";
        cout << "2 - Fechas \n";
        cout << "3 - Links \n";
        cout << "4 - Notes \n";
        cout << "5 - Ubicaciones \n";
        cout << "6 - Finalizar \n";
        cout << "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~\n";
        cout << "Eliga que desea ver:  ";
        cin >> choice;
        cout << "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~\n";

        switch (choice) {
        case 1:
            int x;
            x = 1;
            cout << "Tienes 10 Contactos guardados: \n";
            string contacts[10] = { contact1, contact2, contact3, contact4, contact5, contact6, contact7, contact8, contact9, contact10 };
            while (x < 10) {
                cout << contacts[x] << "\n";
                x = x++;
            }
            break;
        }
        switch (choice) {
        case 2:
            int f;
            f = 1;
            cout << "Existen 10 fechas guardadas. \n";
            string dates[10] = { date1, date2, date3, date4, date5, date6, date7, date8, date9, date10 };
            while (f < 10) {
                cout << dates[f] << "\n";
                f = f++;
            }
            break;
        }
        switch (choice) {
        case 3:
            int l;
            cout << "Tienes 10 links guardados: ";
            l = 1;
            string links[10]{ link1, link2, link3, link4, link5, link6, link7, link8, link9, link10 };
            while (l < 10) {
                cout << links[l] << "\n";
                l = l++;
            }
            break;
        }

        switch (choice) {
        case 4:
            int n;
            n = 1;
            cout << "Estos son sus notes guardados: ";
            string notes[10]{ note1, note2, note3, note4, note5, note6, note7, note8, note9, note10 };
            while (n < 10) {
                cout << notes[n] << "\n";
                n = n++;
            }
            break;
        }
        switch (choice) {
        case 5:
            int u;
            u = 1;
            cout << "Existen 10 ubicaciones guardadas.: ";
            string ubicaciones[10]{ ubi1, ubi2, ubi3, ubi4, ubi5, ubi6, ubi7, ubi8, ubi9, ubi10 };
            while (u < 10) {
                cout << ubicaciones[u] << "\n";
                u = u++;
            }
            break;
        }

        switch (choice) {
        case 6:
            cout << "El programa a finalizado, gracias por utilizar. \n"; //finaliza el programa
            break;
        }

        // Estos finalizaran el programa si el usuario no escoge una de las opciones en pantalla.
        if (choice > 6) {
            cout << "Input invalido. Escoga una de las opciones presentadas en pantalla. \n";
        }
        else if (choice == 0) {
            cout << "Input invalido. Escoga una de las opciones en pantalla.";
        }
        else if (choice < 0) {
            cout << "input invalido. Porfavor escoga una de las opciones en pantalla \n";
        }
        return 0;


    }

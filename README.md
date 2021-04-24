# Mini-Interpreter-Yacc-Lex

A small interpreter for our own C-like programming language.

## Built With

* LEX
* YACC

## Authors

* **Gutu Tiberiu** 
* **Emanuel Tuca** 

## Demo Code


```
float xF := 7.6;
const int var1 := 2;
int yF;
float fvar1 := 4.0;
const float const_fvar1 := 4.0;
bool adevarat := true;
bool fals := false;
char ch := 'd';
const char ch_const := 'd';
string Lastname := "Tuca";
string name := "Emanuel";
int z := 17;
int x[10] := {1, 2, 3, 4, 5, 6, 7, 8};
int y[10];
float xA[20] := {1.2, 2.5, 0.00002};
char Tiberiu[8] := {'T', 'i', 'b', 'e', 'r', 'i', 'u'};
string Emanuel[2] := {"Emanuel", "Tuca"};
bool aha[2];
int testVar := 2;
int a := 2;
int b := 5;
int c := 6;
int wi:= 0;
int ii:= 0;
caps obiect {
    float first;
    bool second;
    const float third := 5.2;
    int array[13];
};

int sum(int x, int y);
int sum(int x, int y)
{
    int one;
    int two;
    int three;
};

{
    while( wi <= 5 )
        {

            wi := wi + 1;
        };

    for(ii := 0; ii < 10; ii := ii + 1)
        {
            ii := b;
        };

    if( wi <= 5)
    {
        ii := 72;

    };

    a:= sum(wi+ii, ii+c);

    eval( (2 * 6) / 2);

    
    testVar := testVar - 5;
    testVar := testVar % 2;
    testVar := x[1] + x[5];
    xF := xF + xF;

    b :=  c * (a + a);
    x[1] := 5;

    a := a + a;
    print ( a );
    Emanuel[0] := "First" + "Second";

    print ( Emanuel[] );
    
    name := name + Lastname;
    a := sum(a, b);

    print ( varTable );

    
}
```




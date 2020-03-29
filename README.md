GHOST PROGRAMMING LANGUAGE

Tunahan Burak Dirlik

BNF FORM 
-- Operators --
<multipication_operator> ::= *
<division_operator> ::= /
<addition_operator> ::= + | -
<relational_operator> ::= < | > | <= | >=
<comment> ::= ## <characters>
<character> ::= <upper_case_letter> | <lower_case_letter> 
                                    | <digit> 
                                    | ! 
                                    | ' 
                                    | ^ 
                                    | # 
                                    | + 
                                    | - 
                                    | % 
                                    | & 
                                    | / 
                                    | ( 
                                    | ) 
                                    | = 
                                    | ? 
                                    | * 
                                    | < 
                                    | > 
                                    | - 
                                    | \ 
                                    | . 
                                    | ,
<upper_case_letter> ::= A | B | C | … | Z | _
<lower_case_letter> ::= a | b | c | … | z | _
<digit> → 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9
<sign> ::= + | -
<type_name> ::= int | db | l | cc | bn
<data_type> ::= array
<int> ::= <sign> ? <number>
<array type> ::= <type><> [ ]
<boolean literal> ::= true | false
<method declaration> ::= <method header> <method body>
<method header> ::= <method modifiers>? <result type> <method declarator> 
<result type> ::= <type> | v
<method modifiers> ::= <method modifier> | <method modifiers> <method modifier>
<method modifier> ::= pr| pb| stt
<method declarator> ::= <identifier> ( <formal parameter list>? 
<method body> ::= <block> 
<result type> ::= <type> | void
<if then statement>::= if ( <expression> ) <statement>
<else statement>::=  elif <statement>
<selection-statement> ::= if ( <expression> ) <statement>
                        | if ( <expression> ) <statement> elif<statement>
<iteration-statement> ::= while ( <expression> ) <statement>
<while statement> ::= w( <expression> ) <statement>
<expression-statement> ::= {<expression>}? :
<statement> ::= | <expression-statement>
<expression-statement> ::= {<expression>}? :
<for statement> ::= f( <for init>? : <expression>? : <for update>? ) <statement>
<for init> ::= <statement expression list> | <local variable declaration>
<for update> ::= <statement expression list>
<statement expression list> ::= <statement expression> | <statement expression list> , <statement expression>
<return statement> ::= return <expression>? :
<variable declarators> ::= <variable declarator> | <variable declarators> , <variable declarator>
<variable declarator> ::= <variable declarator id> | <variable declarator id> = <variable initializer>
<variable declarator id> ::= <identifier> | <variable declarator id> [ ]
<variable initializer> ::= <expression> | <array initializer>
<empty statement> ::= :
<static initializer> ::= stt <block>
<scan_statement> :: = sc <var_name>
<priny_statement> :: show <expression>

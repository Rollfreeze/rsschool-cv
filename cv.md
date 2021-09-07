# 1 Ilin Egor
## 2 My contacts:
    telegram: https://t.me/erglinskiy
    phone: +79082261460
## 3 About me:
    I am a purposeful person who dreams about becoming a demanded web-developer.
    
    My priorities are learning useful courses like RS-School and using new knowledge for web-developing.
    My strong side is my perseverance. If I have a certain goal, I do everything to complete it.
    I had an internship experience of 1С developing, but after 3 months studing and working with it I understood that I didnt like it.
    However I proved to myself that I am more than capable of completing assigned goals.

    Now I am working as a theacher of programming for children.

## 4 Hardware-skills:
    Languages: Python, C++, C#, SQL, UML
    Development tools: VS Code, Visual Studio

## 5 Code examples:
    You can check my code examples in my git portfolio.
    Link: https://github.com/Rollfreeze?tab=repositories

    '''C++
    void looking_for_minus_elements(int** A, int S, int K)
    {
        int zeroes = 0;
        int amount = 0;
        int zero_amount = 0;


        for (int i = 0; i < K; i++)
        {
            for (int j = 0; j < S; j++)
            {
                if (A[i][j] == 0)
                {
                    zero_amount++;
                }
            }
        }

        if (zero_amount == S * K)
        {
            cout << "the whole array consists of zero elements only " << endl;
        }
        else if (zero_amount == 0)
        {
            cout << "the array has no any zero element" << endl;
        }
        else
        {
            for (int i = 0; i < K; i++)
            {
                for (int j = 0; j < S; j++)
                {
                    if (A[i][j] == 0)
                    {
                        for (int s = 0; s < S; s++)
                        {
                            if (A[i][s] < 0)
                            {
                                amount++;
                            }
                        }
                        
                        if (amount == 0)
                        {
                            cout << "Despite we have the 0 element in the string number " << i << ", we have no any minus elements in it" << endl;
                        }

                        else
                        {
                            cout << "The string number " << i << " has " << amount << " minus elements" << endl;
                            amount = 0;
                        }
                    }
                }
            }
        }
    }
    '''

## 6 Work experience:
    I used to train 1C developing via 1С franchising firm in my Town;
    As part of the training course of the institute I have learnt C++ and Python well. I created many projects there, but more important for me is creating client-server application on Python and SQL with pretty good GUI (QT-Designer). I like this project because it's compilation of my knowledge.

    I also have learnt 2 courses for Junior-Development and created 2 simple sites.

    courses:
        * https://brainscloud.ru/landing/html-css
        * https://html.dmitrylavrik.ru/?utm=site-courses

    My sites:
        * https://github.com/Rollfreeze/Wegy-Template
        * https://github.com/Rollfreeze/Myself

## 7 Education:
    I am a student of 4-th course of Admiral Makarov State University of Maritime and Inland Shipping.
    My speciality is a cyber security.

## 8 English:
    My English level is approximately B1
    I traveld a lot with my parents when I was 15-17 years old and I could practice my English with other people who speaked it.

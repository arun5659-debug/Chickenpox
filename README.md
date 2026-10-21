# Chickenpox
Chickenpox is a contagious disease caused by the varicella-zoster virus. It causes an itchy rash with small, fluid-filled blisters, fever, tiredness, and headache. It spreads through the air and direct contact with blisters. Vaccination helps prevent chickenpox and reduces the risk of severe illness.
**Common symptoms**
           - 🌡️ Fever
           - Itchy red spots that turn into fluid-filled blisters
           - Tiredness and weakness
           - Headache and loss of appetite

c programming 

#include <stdio.h>
int main()
{
    int choice;
    printf("\n====================================\n");
    printf("      CHICKENPOX AWARENESS\n");
    printf("====================================\n");
    printf("\n1. About Chickenpox");
    printf("\n2. Symptoms");
    printf("\n3. Prevention");
    printf("\n4. Medical Advice");
    printf("\n5. Exit");
    do
    {
        printf("\n\nEnter your choice (1-5): ");
        scanf("%d", &choice);
        switch (choice)
        {
            case 1:
                printf("\n--- About Chickenpox ---\n");
                printf("Chickenpox is a contagious viral infection.\n");
                printf("It is caused by the varicella-zoster virus.\n");
                printf("It commonly causes an itchy skin rash.\n");
                break;
            case 2:
                printf("\n--- Symptoms ---\n");
                printf("1. Itchy red skin rash\n");
                printf("2. Fluid-filled blisters\n");
                printf("3. Fever\n");
                printf("4. Tiredness and weakness\n");
                printf("5. Headache and loss of appetite\n");
                break;
            case 3:
                printf("\n--- Prevention ---\n");
                printf("1. Ask a doctor about vaccination.\n");
                printf("2. Wash hands regularly.\n");
                printf("3. Avoid scratching the rash.\n");
                printf("4. Drink fluids and get enough rest.\n");
                printf("5. Avoid contact while contagious.\n");
                break;
            case 4:
                printf("\n--- Medical Advice ---\n");
                printf("Contact a healthcare professional\n");
                printf("if you suspect chickenpox.\n");
                printf("Seek urgent care for breathing difficulty,\n");
                printf("confusion, or a severe headache.\n");
                printf("This program cannot diagnose illness.\n");
                break;
            case 5:
                printf("\nThank you for using this program!\n");
                break;
            default:
                printf("\nInvalid choice! Enter a number from 1 to 5.\n");
        }
    } while (choice != 5);
    return 0;
}

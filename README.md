# Mini-Quiz-game
It is a simple game to play
#include <stdio.h>

int main() {
    int score = 0;
    char answer;

    printf("===== MINI QUIZ GAME =====\n\n");

    // Question 1
    printf("1. What is the capital of India?\n");
    printf("A. Mumbai\nB. New Delhi\nC. Chennai\nD. Kolkata\n");
    printf("Your answer: ");
    scanf(" %c", &answer);

    if (answer == 'B' || answer == 'b') {
        printf("Correct!\n\n");
        score++;
    } else {
        printf("Wrong! Correct answer is B\n\n");
    }

    // Question 2
    printf("2. Which language is used to write C programs?\n");
    printf("A. Python\nB. Java\nC. C\nD. HTML\n");
    printf("Your answer: ");
    scanf(" %c", &answer);

    if (answer == 'C' || answer == 'c') {
        printf("Correct!\n\n");
        score++;
    } else {
        printf("Wrong! Correct answer is C\n\n");
    }

    // Question 3
    printf("3. Who is known as the father of C language?\n");
    printf("A. Dennis Ritchie\nB. James Gosling\nC. Bjarne Stroustrup\nD. Guido van Rossum\n");
    printf("Your answer: ");
    scanf(" %c", &answer);

    if (answer == 'A' || answer == 'a') {
        printf("Correct!\n\n");
        score++;
    } else {
        printf("Wrong! Correct answer is A\n\n");
    }

    // Final Score
    printf("===== QUIZ COMPLETED =====\n");
    printf("Your Score: %d / 3\n", score);

    if (score == 3)
        printf("Excellent! 🎉\n");
    else if (score == 2)
        printf("Good job 👍\n");
    else
        printf("Better luck next time 😊\n");

    return 0;
}

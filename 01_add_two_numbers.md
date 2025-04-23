{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "authorship_tag": "ABX9TyNRR5eqmYZIWf2H7ieEJRwV",
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/Salikasyed1/Project-4-Assignments/blob/main/01_add_two_numbers.md\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "\"\"\"\n",
        "Program: Sum Calculator\n",
        "------------------------\n",
        "This program takes two integers from the user,\n",
        "calculates their sum, and displays the result.\n",
        "Great for practicing basic input/output in Python.\n",
        "\"\"\"\n",
        "\n",
        "def main():\n",
        "    print(\"Welcome to the Sum Calculator!\\n\")\n",
        "\n",
        "    try:\n",
        "        first_number = int(input(\"Please enter the first number: \"))\n",
        "        second_number = int(input(\"Please enter the second number: \"))\n",
        "\n",
        "        result = first_number + second_number\n",
        "\n",
        "        print(f\"\\nThe sum of {first_number} and {second_number} is: {result}\")\n",
        "\n",
        "    except ValueError:\n",
        "        print(\"\\nOops! Please enter only valid integers.\")\n",
        "\n",
        "# Entry point of the program\n",
        "if __name__ == '__main__':\n",
        "    main()\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "ZzvHO3w5QYIX",
        "outputId": "fa6880e5-b570-4082-9538-d5b26f583863"
      },
      "execution_count": 2,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Welcome to the Sum Calculator!\n",
            "\n",
            "Please enter the first number: 2\n",
            "Please enter the second number: 4\n",
            "\n",
            "The sum of 2 and 4 is: 6\n"
          ]
        }
      ]
    }
  ]
}
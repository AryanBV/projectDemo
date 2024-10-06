# New Project

    This project was created from local system

# What's new
    HTML
    CSS
    JavaScript

# Time Complexity:
    The time complexity is O(n), where n is the length of s2, because we only loop through s2 once and compare the frequency arrays in constant time (26 elements).

# Space Complexity:
    The space complexity is O(1) since we are using fixed-size arrays (26 elements for the alphabet).

# Approach:
    Character Frequency Count: We first count the frequency of characters in s1 and then slide a window of length equal to s1 over s2. For each window, we count the frequency of characters and compare it with the frequency count of s1.

    Sliding Window: Instead of recalculating the frequency for every new window, we can update the frequency by removing the effect of the character that is sliding out of the window and adding the effect of the new character coming into the window.

    Compare Frequencies: If the frequency of characters in the current window matches the frequency of s1, we return true.
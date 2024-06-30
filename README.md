## Balanced Brackets Solution

### Complexity Analysis

1. **Time Complexity**
   The time complexity of this algorithm is O(n), where n is the length of the string. The algorithm processes each character in the string exactly once. If the character is an opening bracket, it is added to the stack. If the character is a closing bracket, the algorithm checks whether there is a matching opening bracket on the stack. Each push and pop operation on the stack is O(1), so the total complexity is O(n).

2. **Space Complexity**
   The space complexity of this algorithm is also O(n). In the worst case, all characters in the string are opening brackets, meaning all these characters will be stored in the stack. Thus, the space required to store the stack is O(n).

### Example Input and Output

```plaintext
Input: { [ ( ) ] }
Output: YES

Input: { [ ( ] ) }
Output: NO

Input: { ( ( [ ] ) [ ] ) [ ] }
Output: YES

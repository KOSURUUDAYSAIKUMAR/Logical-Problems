# Logical-Problems

print(longestValidParentheses("(()"), "1--------") // Output: "()"
print(longestValidParentheses(")()())"), "2--------") // Output: "()()"
print(longestValidParentheses(""), "3--------") // Output: ""
print(longestValidParentheses("))(())())"), "4--------") // (()) --- (())()
print(longestValidParentheses("()((()())"), "5--------") // (()())
print(longestValidParentheses("()(){{}}[[]]"), "6--------") // {{}}[[]]
print(longestValidParentheses("()(){}{}[][]"), "7--------") // ()(){}{}[][]
print(longestValidParentheses("()(())"), "8--------") // (())()
print(longestValidParentheses("()(())((()))"), "9--------") // ((())) // ()(())((()))
print(longestValidParentheses("(){{}}[[[]]]"), "10--------") // [[[]]]
print(longestValidParentheses("(){{{}}}[[]]"), "11--------") // {{{}}}
print(longestValidParentheses("(){{{}}}[[[]]]"), "12--------") // {{{}}}[[[]]]
print(longestValidParentheses("(()()){}[]"), "13--------") // (()())
print(longestValidParentheses("]][[]][]]"), "14--------") // [[]] - [[]][]
print(longestValidParentheses("[][[[][]]"), "15--------") // [[][]]
print(longestValidParentheses("(){{{}}}[[[]]]((()))"), "16--------") // {{{}}}[[[]]]((()))
print(longestValidParentheses(" "), "17--------") // ""
print(longestValidParentheses("(((([}{]"), "18--------") // ""
print(longestValidParentheses("(((("), "19--------") // ""
print(longestValidParentheses("{{{"), "20--------") // ""
print(longestValidParentheses("[[["), "21--------") // ""
print(longestValidParentheses("()"), "22--------") // ()
print(longestValidParentheses("{}"), "23--------") // {}
print(longestValidParentheses("[]"), "24--------") // []
print(longestValidParentheses("((([[}]]))"), "25--------") // ""
print(longestValidParentheses("[[[((]]))"), "26--------") // ""
print(longestValidParentheses("()(){}"), "27--------") // () ()
print(longestValidParentheses("( ) ( ) ]"), "28--------") // ( ) ( )
print(longestValidParentheses("[ [ ( ) ( { ) ] ]"), "29--------") // ( )
print(longestValidParentheses("[[[][]]"), "30--------") // [[][]]
print(longestValidParentheses("[][[[][[]]]]"), "31--------") // [[[][[]]]] // [][[[][[]]]]
print(longestValidParentheses("((([[]])))"), "32--------")  // [[]]
print(longestValidParentheses("[[[{{()}}]]]"), "33--------") // ()
print(longestValidParentheses("[[[{{(}}]]]"), "34--------") // ""
print(longestValidParentheses(")()()("), "35--------") // "()()"
print(longestValidParentheses("[][[[]]"), "36--------") // [[]]
print(longestValidParentheses("(){}{}"), "37--------") // {}{}
print(longestValidParentheses("(){}()"), "38--------") // "(){}()" --- verify
print(longestValidParentheses("()()()"), "39--------") // ()()()
print(longestValidParentheses("()[]()[]()"), "40--------") // "()[]()[]()" --- verify
print(longestValidParentheses("()[][]"), "41--------") // "[][]"
print(longestValidParentheses("{[()()]{[][]"), "42--------") // [()()]

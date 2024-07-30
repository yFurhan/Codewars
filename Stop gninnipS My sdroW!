public class SpinWords {
    public static String spinWords(String sentence) {
        // Split the sentence into words
        String[] words = sentence.split(" ");
        
        // Process each word
        for (int i = 0; i < words.length; i++) {
            if (words[i].length() >= 5) {
                // Reverse words with 5 or more letters
                words[i] = new StringBuilder(words[i]).reverse().toString();
            }
        }
        
        // Join the words back into a single string
        return String.join(" ", words);
    }

    public static void main(String[] args) {
        // Test cases
        System.out.println(spinWords("Hey fellow warriors"));  // Output: "Hey wollef sroirraw"
        System.out.println(spinWords("This is a test"));       // Output: "This is a test"
        System.out.println(spinWords("This is another test")); // Output: "This is rehtona test"
    }
}

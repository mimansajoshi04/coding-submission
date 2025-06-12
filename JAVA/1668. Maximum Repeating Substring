class Solution {
    public int maxRepeating(String sequence, String word) {
        int k = 0;
        StringBuilder sb = new StringBuilder();

        while (true) {
            sb.append(word);
            if (sequence.contains(sb.toString())) {
                k++;
            } else {
                break;
            }
        }

        return k;
    }
}

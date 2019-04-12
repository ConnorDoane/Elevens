1. public String flip() {
    int random = (int) Math.random() * 3;
    if (random < 2) return "heads";
    else return "tails";
}

2. public boolean arePermutations(int[] firstArray, int[] secondArray) {
    if (!firstArray.length == secondArray.length) return false;
    for (int i = 0; i < firstArray.length; i++) {
        if (secondArray.indexOf(firstArray[i]) == -1) return false; 
    }
    return true;
}

3. 3, 2, 1, 0
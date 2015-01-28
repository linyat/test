# test
def main():
    print("This program is calculating the average word length in a sentence.\n")
    Sentence = input(" Please enter a sentence:")
    Words = Sentence.split(" ")
    Wordavg = sum(map(len, Words))/len (Words)
    print ("The average of word:", Wordavg)


main()

# trialanderroranxious
def current_feeling():
    print "Hello, this is the beginning of the mindfulness program, please take a deep breath and open your mind"
    print "How are you feeling today?"
    answer = raw_input("Type a for anxious or b for content or c for angry or d for sad and then hit 'Enter'.").lower()
    if answer == "anxious" or answer == "a":
        print "Are you avoiding something today?"
        answer = raw_input("Type y for yes or n for no and then hit 'Enter'.")
        if answer == "yes" or answer == "y":
            print "If you created a list of pros and cons...would you get more benefit to face what you're avoiding " \
                  "or peace of mind to put your energy towards something else?"
            answer = raw_input("Type f for face it or s for something else and then hit 'Enter'.")
            if answer == "face it" or answer == "f":
                print "Think of 3 things that help you relax, listening to music, taking a walk, or talking to a friend."  \
                      "You can keep yourself busy until you need to take on what you're avoiding, and you can prepare for" \
                      "what's to come by listing any fears you might be having and then rationalizing each one with a" \
                      "realistic and positive response. Would you like to see an example?"
                answer = raw_input("Type y for yes or n for no and then hit 'Enter'.")
                if answer == "yes" or answer == "y":
                    print "Here's an example: " \
                          "my list is based on being nervous attending a function that's important to me, but allot of  " \
                          "will be attending." \
                          "1)I don't know allot of people that will be there and that makes me feel uncomfortable because I don't" \
                          "know what to expect." \
                          "counter: I need to be more social because it's a personal goal of mine, and if I don't take a chance" \
                          "and try something new, I am missing out on an opportunity to improve myself and possibly meet new" \
                          "people" \
                          "2)Everyone will think I'm strange and I might say something I regret" \
                          "counter: I can prepare myself for this event by deciding ahead of time, on a few starter topics I'm comfortable talking" \
                          "about. I need to try to be less critical of myself so I can be the best version of me." \
                          "Try to do some steady breathing for 15 minutes with yours eyes closed, if not possible just find somewhere " \
                          "quiet and without distractions and rest your mind and thoughts and tell yourself you can handle this."
                elif answer == "no" or answer == "n":
                    print "Try to do a some steady breathing for 15 minutes with your eyes closed, if not possible just find somewhere " \
                          "quiet and without distractions and rest your mind and thoughts and tell yourself you can handle this."

        elif answer == "no" or answer == "n":
            print "Are you feeling nervous/anxious because of a past conflict or situation, or something else?"
            answer == raw_input("Type p for past conflict or s for something else and then hit 'Enter'.")
            if answer == "past" or answer == "p":
                print "Insert coming to explore a secondary question that prompts user to open mind to what is now"
            elif answer == "something else" or answer == "s":
                print "Third and fourth question prompt to be input later."
        else:
            print "You didn't make a choice, try again"
    elif answer == "content" or answer == "b":
        print "Today, would be a good day to record some positive thoughts, would you like a guide to do that?"
    elif answer == "angry" or answer == "c":
        print "Are you prevented from doing something you want?"
    elif answer == "sad" or answer == "d":
        print "Would you like to create an activity sheet, today?"
    else:
        print "You didn't make a choice, try again."
        current_feeling()

current_feeling()

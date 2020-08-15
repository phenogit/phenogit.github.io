---
layout: page
title: Kit's Korner
permalink: /kit-korner-notes/
---

currently on Occam's Razor - 2011/2/13

## Non-Competitive Bidding
### Bidding Tree

    1D: 1) Vulnerable 1/2 seat 11-15, 2+d, if balanced 11-13
        2) 3/4 seat 11-15, 2+d, if balanced 11-14
        1H
            2H: Always 4h, no singleton or voids, 11-13
                2S: Unspecified short suit game or slam try
                    3C: Ask, coded response
                2N: Long/help suit game try in clubs
                3C: Long/help suit game try in diamonds
                3D: Long/help suit game try in spades
                    4H
                        4S: RKC
                        4N: Ask in spades
                        5C: Ask in clubs
                        5D: Ask in diamonds
                        5H: General invite
                        5S: Grand slam force
                        5N: Pick a slam
                3H: Semi-preemptive
                3N: Offer to play
                3S: Natural slam try
                4C: Natural slam try
                4D: Natural slam try
                4S: RKC
            3H: Promises a singleton/void, regardless of strenth, not worth forcing to game
    
    1H
        1S
            1N: 1) Non-vulnerable shows 13-15
            2S: 3 card support possible
        1N: Semi-forcing, permitted to pass with min 5-3-3-2 hand
        2C
            2D: 4+ card suit
            2H: 6 card suit
            2S: 4+ card suit
            2N: 13-15
        2D
            3D: Shows no extra, either in shape or strength

    1N: 1) Non-vulnerable 1/2 seat 10-12
        2) 3/4 seat 15-17
        2C: Non-game forcing Staymen
        2D: Game-forcing Stayman
            2H
                xx
                    3H: 5 card suit

    2C: 10-15 points, 6+c, may have 4 or even 5-card major
        2D: Artificial query
            2H: Some 4 card major
                2S: Artificial query, find major and strength
            2S: No major, some shortness, any strength
                2N: Artificial query, find shortness and strength
                    3C: Minimum
                        3D: Artificial query, show shortness in coded manner
                    3H: Non-minimum, heart shortness
                        3N: To play
                        4C: Natural force, slam interest
                            4D: RKCB
                            4H: Cue bid
                            4S: Cue bid
                            4N: Cue bid for diamonds
                            5C: Sign-off
                            If either person bids 4S cuebid, 4N is last train
                            Once cuebidding starts, there is no RKC
                            RKC is 03/14; king is for specific king; 03/14 with void starting at 5D; number of kings if void shown
                        4D: RKCB for clubs
                        5C: To play
            2N: Balanced, non-minimum
            3C: Balanced, minimum
        2S: Natural force, 5+ spades, may stop in 2N, 3C or 3S
        2N: Forces 3C, either
            1) Planning to pass 3C
            2) 2-suiter game forcing hand not including clubs
            3) Slam try in clubs
            3C
                P     : To play
                3D    : 2 suiter, 5-5 game forcing
                3H    : Spade-diamond, 5-5 game forcing
                3S    : 2 suiter, 5-5 game forcing
                Higher: Some kind of club slam try
        3C: Forces 3D
            3D
                P     : To play
                Higher: Slam tries
        3D: Natural invite
    2D: Weak 2 in one of the majors

## Competitive Bidding
### Meta Rules
    Forcing pass doesn't show extra strength.
    All it shows is more of an offensive orentation.

    Voluntarily and non-premptively jumps to game creates a force

    Ｐenalty X of 1N puts partnership in force
    Ｅ.g.
        1D-(1N)-X
        follow up
            1D-(1N)-X-2S;
            ??
                X : Penalty
                2N: Both minors, diamond emphasis
                    Possibly both red suits with longer diamond, he pulls 3C to 3D
                3C: Both minors, club emphasis

            1D-(1N)-X-2S;
            P -(P ) -??
                    X : Penalty
                        * Partner pulls to 2N is probably 3 suited takeout
                    2N: Takeout, asking for better minor
                    3C: Natural, non-forcing
                    3D: Natural, non-forcing
                    3H: Natural, non-forcing

    Pass of a redouble of a takeout double is always penalties, unless both of the following conditions are met:
        1) The opponents are at the 1-level.
        2) The partner of the doubler is in front of the suit doubled.
    Ｅ.g.
        a. (1S)-X-(XX)-Pass is non-committal. 
        b. (1S)-P-(P )-X;
           (XX)-Pass is penalties. 
        c. (1S)-(P)-(2S)-P;
           (P)- (P)-(XX)-Pass is penalties.

### Misc
    1N!-(2D@)-4D#
        !: 10-12
        @: Diamonds and a major
        #: Transfer

    (P)-1S-(2S!)-??
        !: Hearts and clubs

        X : Interest in defending, likely not spade support
        2N: Natural, invitational (when enemy suits are known)
        3S: To play, no game interest
        3H: Limit raise or better, puts you in a force unless you get a chance to clarify you only have a limit raise
        4H: Splinter, slam interest in spades
        4S: Any hand, partner must pass. Does not create a force
            If the next hand bids, partner may not bid 5S on his own
            If he wishes to bid 5S he doubles -> penalty double not available

    cont'd
    (P )-1S -(2S!)-3H;
    (5H)-5S!
        !: Weaker than pass (forcing) followed by a pull

    2D-(X!)-??
        !: Either a takeout double of spades or some strong hand
        
        P : If 4th seat bids, partner shuts up. 
           If 4th seat passes, partner passes (ending the auction) if he holds 3+ diamonds but he shows his suit with fewer than 3 diamonds. 
           On hands with 4+ diamonds and short in a major this will often avoid going for a number since 4th seat needs a diamond stack to pass.
        XX: Forces partner to bid 2H, after which you place the contract. This allows you to stop in 2H when you have a long heart suit.
        2H: Pass or correct
        2S: Pass or correct
        2N: Asking about partner's hand. At least game-invitational.
        3C: Shows hearts, asks about heart length. At least game invitational.
        3D: Shows spades, asks about spade length. At least game invitational.
        3H: Pass or correct
        3S: Pass or correct
        3N: End of auction
        4C: Asks partner to transfer to his suit.
        4D: Asks partner to bid his suit.
        4H: End of auction
        4S: End of auction
        

## Modules

    RKC(03/14)
    4S RKC, follow-ups other than 5H/6H signoff
        5C: Ask for queen of trumps
        5D: Ask for queen of trumps
        5S: Ask for specific kings
            5S does not promise all keycards, if responder wants to bid grand slam, he bids 6N
            Partner shows kings up the line, showing the lowest king
                Make a bid corresponding to a higher king asks partner to bid 6N if holding that king
        5N: Pick a slam
        6C: Natural offer to play
        6D: Natural offer to play

    Opps 2S Balancing Module
    E.g.
        (1N)-P-(2H)-??
        X: Primarily lead-directing

        (1N)-P-(2H)-P ;
        (2S)-P-(P )-??
            X: a) 3-suited
            b) Hearts and clubs
            c) Red suits, longer diamonds
            Follow up:
                2N: Asks if you have diamonds, 
                    if you do you bid 3D
                    else if you have h+c, you bid 3C

    3-level Responsive Alternative
    We use this treatment all the time at the 3-level, when partner has opened the bidding overcalled, or made a takeout double, and the next hand bids 3C, 3D, or 3H
    E.g.
    (2C!)-2S-(3C)-??
        !: Precision

        X : Relay to next cheapest suit, assumed to be weak somewhere
            But followed by cue bid or 3N shows regular responsive
        3D: Natural and forcing
        3H: Natural and forcing
        3S: Limit raise
        4C: Slam interest, shows nothing about clubs
        4S: What it sounds like, creates force


## Carding
#### NT
##### General
    UDCA including discards except for trick 1 where it is standard signals
    Smith echo
    In middle of hand, T/9 show 0 or 2 higher; other spot card leads are generally attitude
    If giving count, first played card is upside-down count, if not it is standard count

##### Opening Leads
    9 or higher is considered an honor
    A from AK
    Non-partner's suit
        Rusinow(lower of touching honors with more than a doubleton)
        K is power lead 
    Partner's suit
        Standard leads
    Attitude leads for small card

#### Suit
##### General
    Suit-preference at trick 1
        T/9/8 high side suit
        2/3/4 low side suit
        6/5/7 encouraging
        Make least damaging signal if no suitable card
    UDCA
    Standard current count on later plays in a suit
    Standard current count for discard
    Splitting honors show 0 or 2 higher

##### Opening Leads
    Third from even, smallest from odd, top of a doubleton
    5th best from 7 card suit if there is known length
    From 3 small, high or low, when in doubt - count
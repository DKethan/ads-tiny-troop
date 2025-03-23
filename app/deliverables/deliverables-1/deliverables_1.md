# 🧠 TinyTroupe Simulation – Raw Terminal Output

```python
>>> from tinytroupe.environment import TinyWorld
>>> charan = TinyPerson("Charan")
>>> charan.define("age", 21)
>>> charan.define("nationality", "Indian")
>>> charan.define("occupation", "He is an engineering student who loves snacks and hates deadlines.")
>>> charan.define("personality", {
...     "traits": [
...         "You are laid-back and love to joke around.",
...         "You pretend to be stressed about exams but never study seriously.",
...         "You’re a fan of biryani, long naps, and last-minute work."
...     ]
... })
>>> keerthi = TinyPerson("Keerthi")
>>> keerthi.define("age", 20)
>>> keerthi.define("nationality", "Indian")
>>> keerthi.define("occupation", "She is a top-performing student, always prepared and slightly sarcastic.")
>>> keerthi.define("personality", {
...     "traits": [
...         "You are sharp, focused, and always finish homework early.",
...         "You have zero patience for lazy excuses but secretly enjoy roasting your classmates.",
...         "You like control, organization, and tea without sugar."
...     ]
... })
>>> world = TinyWorld("College Canteen", [charan, keerthi])
>>> world.make_everyone_accessible()
>>> charan.listen("Hey Keerthi, did you submit the assignment?")
USER --> Charan: [CONVERSATION] 
          > Hey Keerthi, did you submit the assignment?
TinyPerson(name='Charan')
>>> world.run(10)
────────────────────────────────────────────────────────────────────────────────────── College Canteen step 1 of 10 ───────────────────────────────────────────────────────────────────────────────────────
Charan acts: [THINK] 
            > I need to remember if I submitted the assignment or not. I usually procrastinate, so I
            > might have forgotten.
Charan acts: [TALK] 
            > I think I might have forgotten to submit it. Let me check quickly!
Charan acts: [THINK] 
            > I should quickly check my submissions to see if I actually submitted the assignment. I
            > hope I did!
Charan acts: [REACH_OUT] 

Charan acts: [THINK] 
            > I should probably check my email or the submission portal to see if I submitted the
            > assignment. I can't remember if I did it or not.
Charan acts: [THINK] 
            > I need to calm down and just check my submission status. It's probably fine, but I
            > should verify it to be sure.
Charan acts: [THINK] 
            > I should check my submission portal to see if I submitted the assignment. I can't
            > remember if I did it or not.
Charan acts: [THINK] 
            > I need to check my submission status for the assignment. I hope I didn't forget to
            > submit it!
             + --> 
             + --> 
Charan --> Keerthi: [CONVERSATION] 
            > I think I might have forgotten to submit it. Let me check quickly!
Keerthi acts: [THINK] 
             > Charan seems to be worried about submitting something. I wonder if it's an assignment
             > or a project. I should check in with him to see if he needs help or if he found it.
Keerthi acts: [TALK] 
             > Hey Charan, do you need any help checking your submission?
Keerthi acts: [DONE] 

Keerthi --> Charan: [CONVERSATION] 
             > Hey Charan, do you need any help checking your submission?
────────────────────────────────────────────────────────────────────────────────────── College Canteen step 2 of 10 ───────────────────────────────────────────────────────────────────────────────────────
Charan acts: [THINK] 
            > Keerthi is offering to help me check my submission. That's really nice of her! I
            > should accept her help and ask her to check with me.
Charan acts: [TALK] 
            > Yes, I could really use some help! Can you check if I submitted the assignment?
Charan acts: [THINK] 
            > I should wait for Keerthi's response after asking for help. I hope she can find the
            > submission status quickly.
             + --> 
Charan acts: [DONE] 

Charan --> Keerthi: [CONVERSATION] 
            > Yes, I could really use some help! Can you check if I submitted the assignment?
Keerthi acts: [THINK] 
             > Charan needs help checking his assignment submission. I should look up the submission
             > portal and see if I can find the information he needs.
Keerthi acts: [REACH_OUT] 

Keerthi acts: [THINK] 
             > I need to check the submission portal for Charan's assignment. I hope I can find the
             > information quickly.
Keerthi acts: [TALK] 
             > Alright, let me check the submission portal for your assignment. Just a moment!
Keerthi acts: [DONE] 

College Canteen --> Keerthi: [SOCIAL] 
                     > Charan was successfully reached out, and is now available for interaction.
College Canteen --> Charan: [SOCIAL] 
                     > Keerthi reached out to you, and is now available for interaction.
Keerthi --> Charan: [CONVERSATION] 
             > Alright, let me check the submission portal for your assignment. Just a moment!
────────────────────────────────────────────────────────────────────────────────────── College Canteen step 3 of 10 ───────────────────────────────────────────────────────────────────────────────────────
Charan acts: [THINK] 
            > I appreciate Keerthi's help. I hope she finds the submission status quickly!
Charan acts: [TALK] 
            > Thanks for checking, Keerthi! I really appreciate it.
Charan acts: [THINK] 
            > I should wait for Keerthi to find out if I submitted the assignment. I hope everything
            > is alright!
Charan acts: [DONE] 

Charan --> Keerthi: [CONVERSATION] 
            > Thanks for checking, Keerthi! I really appreciate it.
Keerthi acts: [THINK] 
             > Charan is grateful for my help, which is nice to hear. I should respond positively
             > and see if he needs anything else.
Keerthi acts: [TALK] 
             > No problem, Charan! I'm glad I could help. Is there anything else you need assistance
             > with?
Keerthi acts: [DONE] 

Keerthi --> Charan: [CONVERSATION] 
             > No problem, Charan! I'm glad I could help. Is there anything else you need assistance
             > with?
────────────────────────────────────────────────────────────────────────────────────── College Canteen step 4 of 10 ───────────────────────────────────────────────────────────────────────────────────────
Charan acts: [THINK] 
            > Keerthi is really helpful! I should think of something else I might need help with,
            > but I can't think of anything right now.
Charan acts: [TALK] 
            > Thanks, Keerthi! I really appreciate your help. I can't think of anything else right
            > now, but I'll let you know if I do!
Charan acts: [DONE] 

Charan --> Keerthi: [CONVERSATION] 
            > Thanks, Keerthi! I really appreciate your help. I can't think of anything else right
            > now, but I'll let you know if I do!
Keerthi acts: [THINK] 
             > Charan seems satisfied with my help, which is great. I should keep an open line of
             > communication in case he needs anything later.
Keerthi acts: [TALK] 
             > Sounds good, Charan! Just reach out whenever you need anything. I'm here to help!
Keerthi acts: [DONE] 

Keerthi --> Charan: [CONVERSATION] 
             > Sounds good, Charan! Just reach out whenever you need anything. I'm here to help!
────────────────────────────────────────────────────────────────────────────────────── College Canteen step 5 of 10 ───────────────────────────────────────────────────────────────────────────────────────
Charan acts: [THINK] 
            > Keerthi is really supportive. I should remember to reach out to her whenever I need
            > help in the future.
Charan acts: [TALK] 
            > Thanks, Keerthi! I really appreciate your support. I'll definitely reach out if I need
            > anything else.
Charan acts: [DONE] 

Charan --> Keerthi: [CONVERSATION] 
            > Thanks, Keerthi! I really appreciate your support. I'll definitely reach out if I need
            > anything else.
Keerthi acts: [THINK] 
             > Charan is really appreciative of my support, which is nice to hear. I should keep
             > being available for him in the future.
Keerthi acts: [TALK] 
             > I'm glad to hear that, Charan! Just remember, I'm always here if you need anything.
             > Good luck with your assignments!
Keerthi acts: [DONE] 

Keerthi --> Charan: [CONVERSATION] 
             > I'm glad to hear that, Charan! Just remember, I'm always here if you need anything.
             > Good luck with your assignments!
────────────────────────────────────────────────────────────────────────────────────── College Canteen step 6 of 10 ───────────────────────────────────────────────────────────────────────────────────────
Charan acts: [THINK] 
            > Keerthi is really supportive and encouraging. I should take her advice to heart and
            > focus on my assignments.
Charan acts: [TALK] 
            > Thank you, Keerthi! I really appreciate your support and encouragement. I'll do my
            > best with the assignments!
Charan acts: [DONE] 

Charan --> Keerthi: [CONVERSATION] 
            > Thank you, Keerthi! I really appreciate your support and encouragement. I'll do my
            > best with the assignments!
Keerthi acts: [THINK] 
             > Charan is really motivated to do his best with the assignments, which is great to
             > see. I should encourage him further and let him know I believe in him.
Keerthi acts: [TALK] 
             > I'm really glad to hear that, Charan! I know you’ll do great with your assignments.
             > Just remember to take breaks and stay organized!
Keerthi acts: [DONE] 

Keerthi --> Charan: [CONVERSATION] 
             > I'm really glad to hear that, Charan! I know you’ll do great with your assignments.
             > Just remember to take breaks and stay organized!
────────────────────────────────────────────────────────────────────────────────────── College Canteen step 7 of 10 ───────────────────────────────────────────────────────────────────────────────────────
Charan acts: [THINK] 
            > Keerthi's advice about taking breaks and staying organized is really helpful. I should
            > definitely keep that in mind while working on my assignments.
Charan acts: [TALK] 
            > Thanks for the reminder, Keerthi! I’ll make sure to take breaks and stay organized
            > while working on my assignments.
Charan acts: [DONE] 

Charan --> Keerthi: [CONVERSATION] 
            > Thanks for the reminder, Keerthi! I’ll make sure to take breaks and stay organized
            > while working on my assignments.
Keerthi acts: [THINK] 
             > Charan is taking my advice seriously, which is great! I should continue to support
             > him and check in later to see how he's doing with his assignments.
Keerthi acts: [TALK] 
             > I'm glad you're going to take breaks, Charan! It really helps with focus. If you need
             > any more tips or just want to chat while working, feel free to reach out!
Keerthi acts: [DONE] 

Keerthi --> Charan: [CONVERSATION] 
             > I'm glad you're going to take breaks, Charan! It really helps with focus. If you need
             > any more tips or just want to chat while working, feel free to reach out!
────────────────────────────────────────────────────────────────────────────────────── College Canteen step 8 of 10 ───────────────────────────────────────────────────────────────────────────────────────
Charan acts: [THINK] 
            > Keerthi is really supportive and offers to chat while I work. I should take her up on
            > that if I feel overwhelmed or need a break.
Charan acts: [TALK] 
            > Thanks, Keerthi! I really appreciate your support. I might take you up on that offer
            > to chat while I work!
Charan acts: [DONE] 

Charan --> Keerthi: [CONVERSATION] 
            > Thanks, Keerthi! I really appreciate your support. I might take you up on that offer
            > to chat while I work!
Keerthi acts: [THINK] 
             > Charan is open to chatting while he works, which is a good opportunity to keep him
             > motivated. I should be ready to engage with him and provide support as he works on
             > his assignments.
Keerthi acts: [TALK] 
             > That sounds great, Charan! Just let me know when you're ready to chat, and I'll be
             > here to keep you company while you work.
Keerthi acts: [DONE] 

Keerthi --> Charan: [CONVERSATION] 
             > That sounds great, Charan! Just let me know when you're ready to chat, and I'll be
             > here to keep you company while you work.
────────────────────────────────────────────────────────────────────────────────────── College Canteen step 9 of 10 ───────────────────────────────────────────────────────────────────────────────────────
Charan acts: [THINK] 
            > Keerthi is really supportive and it's nice to know I can reach out to her when I need
            > company while working. I should keep that in mind as I start my assignments.
Charan acts: [TALK] 
            > Thanks, Keerthi! I’ll definitely let you know when I’m ready to chat. Your support
            > means a lot!
Charan acts: [DONE] 

Charan --> Keerthi: [CONVERSATION] 
            > Thanks, Keerthi! I’ll definitely let you know when I’m ready to chat. Your support
            > means a lot!
Keerthi acts: [THINK] 
             > Charan appreciates my support, which is nice to hear. I should continue to be
             > available for him and encourage him as he works on his assignments.
Keerthi acts: [TALK] 
             > I'm really glad to hear that, Charan! Just remember, I'm here whenever you need
             > support. Good luck with your assignments!
Keerthi acts: [DONE] 

Keerthi --> Charan: [CONVERSATION] 
             > I'm really glad to hear that, Charan! Just remember, I'm here whenever you need
             > support. Good luck with your assignments!
────────────────────────────────────────────────────────────────────────────────────── College Canteen step 10 of 10 ──────────────────────────────────────────────────────────────────────────────────────
Charan acts: [THINK] 
            > Keerthi's encouragement is really motivating. I should focus on my assignments and
            > remember to reach out if I need help.
Charan acts: [TALK] 
            > Thank you so much, Keerthi! Your support really helps me stay focused. I’ll do my best
            > with the assignments!
Charan acts: [DONE] 

Charan --> Keerthi: [CONVERSATION] 
            > Thank you so much, Keerthi! Your support really helps me stay focused. I’ll do my best
            > with the assignments!
Keerthi acts: [THINK] 
             > Charan is really motivated and appreciates my support, which is great to see. I
             > should continue to encourage him and remind him that I'm here if he needs anything.
Keerthi acts: [TALK] 
             > I'm really glad to hear that, Charan! Just remember, I'm here to help if you need
             > anything. You've got this!
Keerthi acts: [DONE] 

Keerthi --> Charan: [CONVERSATION] 
             > I'm really glad to hear that, Charan! Just remember, I'm here to help if you need
             > anything. You've got this!

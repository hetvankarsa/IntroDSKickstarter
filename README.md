# IntroDSKickstarter


PROJECT DESCRIPTION
    This project aims in predicting the success rate of Kickstarter projects based on their featues. The labelled dataset is visually explored, and two training models are funded based on the derived features.
    
PREREQUISITES
    In order to run this project, install the Anaconda open-source distribution of Python. Then, visualize the program through the jupyter notebook kernel.
    
IDENTIFIED FEATURES (to be deleted before submitting)
    Roxana - 'category'
             'staff_pick'
             'days_until_deadline' = 'deadline' - 'launched_at'
             'money_per_day' = 'goal' / 'days_until_deadline' (this attribute is in relation with the previous one; one should be chosen)
    Ioana -  
            <p>'goal'<p> 
            <p>'staff_pick' - boolean value: 1 if staff picked the project / 0 if not<p>
            <p>'blurb_length' - length of the project description as a counter of letters and whitespaces<p>
            <p>'period_lc' - number of days between creation and launch of the project<p>
            <p>'period_dl' - number of days between launch and deadline of the project<p>
            <p>'money_pday' - goal / period_dl is the money per day needed for the goal to be met<p>
            <p>'name_length' - length of the project title as a counter of letters and whitespaces<p>

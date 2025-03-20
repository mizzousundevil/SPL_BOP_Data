# SPL_BOP_Data
To improve transparency and accountability, Spotlight PA filed requests under the Right-to-Know Law for data showing every commutation recommendation vote taken by the Board of Pardons in the past 25 years.

# Data dictionary:

Date: The date of the first public hearing in the applicant’s case. Please note, the vote may take place at a subsequent hearing.
Year: The year of the first public hearing.
Administration: The governor in office at the time of the vote. Spotlight PA added this column.
Full name: The name of the applicant
Commutation type: The sentence the applicant is seeking commutation to shorten
County: The county where the crime occurred
Yes Votes: The number of board members voting in favor of the applicant	
No Votes: The number of board members voting against the applicant
Outcome: The outcome of the vote. Spotlight PA added this column.
Minority Vote: The type of vote that was in the minority.
Who voted yes?: The identity of the board member who voted for an application, if it was included in the original data..
Who voted no ?: The identity of the board member who voted against an application, if it was included in the original data.
Additional information: Other information and outcomes included in the original board data, or notes added by Spotlight PA.


# How we cleaned this																
In response to a request under the Right-to-Know Law, the Pennsylvania Board of Pardons provided Spotlight PA with four .xlsx files recording votes taken during public hearings between 2000 and 2025.

Each file contained the date, type of clemency sought, applicant name, applicant county, vote result, and initials of the board member who voted in the minority.

Spotlight PA joined these four files into one database, cleared the original formatting, and created individual columns for each category of information to enable easier analysis. The news organization also added columns: one for the governor in office at the time of the vote, determined by year, and one for the outcome of the vote.

Outcomes were determined using a conditional formula based on board rules for different types of clemency. 

The board must vote unanimously to recommend commutation of a life or death sentence. For all “life” or “death” applications, if there was one or more votes in dissent, the formula returned “denied.” If there were no votes in dissent, the formula returned “approved.”

People can also apply for commutation of their minimum or maximum sentence imposed by a judge when they are serving an indeterminate amount of time. For example, someone 12 years into a 10-15 year sentence might apply to commute their maximum. Similarly, someone nine years into the same sentence might apply to commute their minimum.

In applications seeking commutation of a minimum or maximum sentence, a majority of members must approve. For all “minimum” or “maximum” applications, if the number of “yes” votes exceeded the number of “no” votes, the formula returned “approved.” If yes votes did not exceed no votes, the formula returned “denied.”

Since 1997, board membership has included the lieutenant governor, the attorney general, a psychologist or psychiatrist, a victim advocate, and a corrections expert. In the original data from the state, the identity of board members who voted in the minority were only identified by first and last initials. 

To determine the identity of board members who voted in the minority, Spotlight PA consulted Pennsylvania Senate confirmation records and other public sources. The Board of Pardons later provided a list of current and past members, some with dates of service, that helped validate the identities.

Once a board member was identified, Spotlight PA replaced the initials.

The original data Spotlight PA received from the Board of Pardons recorded votes for applications for pardons.

Unlike commutation applicants, pardon applicants are not regularly identifiable through other means. Though the data is public and available to anyone who files a Right-to-Know Law request, the names of applicants are not otherwise available online.

People who apply for pardons are seeking to scrub the record of their criminal convictions to improve their economic and social stability and remove the stigma associated with a criminal record. By publishing the names of these applicants, Spotlight PA would once again be identifying these people and connecting them with a criminal background.

Because of this, Spotlight PA is not publishing pardons data at this time. The newsroom is still considering ways to publish this data without compromising the anonymity of the applicants.

Contact the reporter

Do you have a question or thought about the data and Board of Pardons? Feel free to contact me at dohl@spotlightpa.org.

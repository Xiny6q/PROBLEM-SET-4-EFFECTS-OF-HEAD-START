Download link :https://programming.engineering/product/problem-set-4-effects-of-head-start/

# PROBLEM-SET-4-EFFECTS-OF-HEAD-START
PROBLEM SET 4: EFFECTS OF HEAD START
Head Start is an early-childhood development program run by the U.S. federal government. It provides health, nutrition, and education services to children from disadvantaged backgrounds.

The dataset https://github.com/tvogl/econ121/raw/main/data/nlsy_kids.Rdata contains a sample of chil-dren of NLSY ’79 participants, some of whom participated in Head Start. All of the children in the sample have at least one sibling also in the sample. The variables are ordered as follows:

head_start – sibdiﬀ relate to head start participation.

mom_id – lnbw were determined prior to Head Start participation. (Note: the PPVT is an early-childhood cognitive test. The other variable names are self-explanatory.)

comp_score_5to6 – comp_score_11to14 are test scores in childhood.

repeat – fphealth are outcomes in the teenage years and young adulthood.

For various reasons, some variables have missing data. You may decide how to deal with missing values on your own.

To install R and RStudio, follow this link. You are encouraged to work in a group of up to 4 members. You may write code together, but you must write verbal answers yourself. Please use a Markdown template for your code. Write verbal answers in the comments within the Markdown file, so that you produce a single PDF with code, results, and writing, which you will upload to Gradescope.

List your group members.

Summarize the data. What can you say about the backgrounds of children who participated in Head Start relative to those who did not?

Using OLS, estimate the association between Head Start participation and age 5-6 test scores. Make sure you compute standard errors correctly. If we assume Head Start participation is exogenous, what can we conclude about the eﬀects of Head Start on test scores? Interpret the magnitude of the estimated coeﬃcient in terms of the standard deviation of test scores. Is it reasonable to assume that Head Start participation is exogenous? Do you think there are likely to be omitted variables at the family level? If so, how do you think they might bias the estimated coeﬃcient?

Now focus on “between mother” variation in Head Start participation and age 5-6 test scores. Create a new data frame in which each observation is a mother, and the variables are the family mean of Head

Start participation and the family mean of the age 5-6 test score. Using OLS, estimate the association between mean Head Start participation and mean test scores across mothers. How does the estimated coeﬃcient compare with the one from question (3)?

Returning to the original data frame, estimate the association between Head Start participation and age 5-6 test scores in a model with mother fixed eﬀects. What do the results imply about the eﬀects of Head Start on test scores? Interpret the magnitude of the estimated eﬀect in terms of the standard deviation of test scores. If the fixed eﬀect results are diﬀerent from questions (3) and (4), explain why. Which estimate most likely reflects the eﬀect of Head Start participation on test scores, and why?

Include pre-Head Start variables as covariates in the regression with mother fixed eﬀects. Explain your choice of covariates. Does the inclusion of covariates change the estimated coeﬃcient on Head Start? What do you conclude about the robustness of the fixed eﬀect estimate of the eﬀect of Head Start?

Some advocates for early-childhood education suggest that the eﬀects of programs like Head Start are long-lasting. Carry out fixed eﬀects analyses of test scores at later ages. Does Head Start participation have similar eﬀects on test scores in later childhood, or do the eﬀects fade out with age? To make the test scores comparable across ages, you can standardize them by subracting the mean and dividing them by the standard deviation.

Estimate fixed eﬀects models of the eﬀect of Head Start on longer-term outcomes besides test scores. Many of these outcomes are binary, but you may use linear models. Interpret your results.

Focusing on one longer-term outcome (your choice), test whether the eﬀect of Head Start participation on the outcome varies by race/ethnicity. Interpret your results.

The Biden administration advocates expanding federal funding for early-childhood education programs, while the Trump administration argued for cuts. Based on your results, which position seems better supported by evidence? Would you feel comfortable using your results to predict the eﬀects of such an expansion? Why or why not?


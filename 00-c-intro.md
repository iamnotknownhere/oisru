# Introduction

A Risk Universe provides a comprehensive view of the possible risks we face. This view is designed to aid in categorisation but also to act as a check on the scope of our risk identification exercises to ensure we don’t miss risks that then take us by surprise when they occur.

The goal of the Open Information Security Risk Uinverse (OISRU) is to provide a model and method independent framework for epressing and categorising security risk.

This framework should be complementary to the Basel II operational risk event types, recognising that information security risk permeates operational risk.

## Risk Statements <-- Risk Scenario

It’s key to understand that a risk event alone is not a risk, at it's most simple it is a risk event and a consequence.

However it is likely as we develop our risk sceanrios that they will consist of the combination or one or more sources, one or more risk events and one or more consequences.

While the description of the risk scenario under consideration can be tailored to use language appropriate to the organisation in scope and the stakeholders or experts that must consider it the undelying statement of the risk that scenario represents can, and should, be standardised using the Open Information Security Risk Universe.

At it's simplest a risk scenario can be truned into a risk statement using:

There is a risk that \<**event**> occurs leading to \<**outcome**> that causes \<**consequence**>.  (Alt <Risk Scenario> = <threat actor> <threat vector/action> <compromise> <impact/consequence>)

An example of a minimal risk structured as above is:

“*There is a risk that financially sensitive data is accidentally emailed to an external recipient leading to an information breach which results in regulatory fines.*”   (Alt <Risk Scenario> = <Third Perty Supplier employee> <misuses/abuses their entitlements> <to compromisee the integrity of the algo trading algorithm> <resulting in direct financial loss of £100K, £25K response cost, £50K replacemnt cost, etc.>)

Adding a source to the risk can aid in explaining the sceanrio such as:

There is a risk that \<**source**> causes \<**event**> to occur leading to \<**outcome**> that causes \<**consequence**>.

An example of a minimal risk structured as above including a source is:

“*There is a risk that a member of staff accidentally emails financially sensitive data to an external recipient leading to a data breach which results in regulatory enforcement.*”

By ensuring that every risk scenario is formally stated in this way it allows comparison between scenarios as well as identifying what coverage of the OSIRU is currently being considered by the organisation and whether that is appropriate.

By adding the significantly correlated risk factors it is possible to start discussing control measures to limit the risk exposure.

A risk statement including risk factors and controls might include the additional statement:

“*The financially sensitive data is market sensitive information before the annual report is published, but the data leakage control is configured to look for financial reports and to prevent their external transmission, and the Outlook autocomplete function is disabled for the period of the production of the annual report.*”

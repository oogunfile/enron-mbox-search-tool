# Enron Search Tool

## Description

`enron_search-tool` is a command-line utility for searching through a data set of emails from the Enron Corporation. 
It allows users to perform exact, case-insensitive searches for one or more terms within the email bodies. Additionally,
users can query emails sent to and from specific individuals and emails exchanged between two people.

## Features

1. **Term Search**: Search for exact, case-insensitive matches for one or more words within email bodies. Only emails
2.  containing all specified terms will be returned.  It ignores duplicate and order of terms.
3. **Address Search**: Obtain all emails sent and received by a specified person using their last and first names as provided in the prompt.
4. **Interaction Search**: Retrieve all emails exchanged between two specified email addresses, listing the sender,
5. receiver, subject, and date for each interaction.

## Usage
 **Term Search**
 **term**: A word to search for in the data set. The search is case-insensitive but exact, meaning neither fuzzy matching nor partial matching 
 is performed.
- The program ignores duplicate terms and term order.
- Example:
  `shell
  $ enron_search term_search how are you doing?

**Address Search**:
enron_search address_search last_name first_name


**Interaction Search**:
enron_search interaction_search address_1 address_2



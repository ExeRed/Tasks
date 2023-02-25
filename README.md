# Tasks
Task from Java

Account_ 
Given a class Account(number: String, balance: Long, locked: boolean), the list accounts of type List<Account> and the method filter(List<T> elems, Predicate<T> predicate) for filtering the given list of type T by the predicate.

The class Account has the following get methods: getNumber(), getBalance(), isLocked() for retrieving the values of the corresponding fields.

Write code for filtering the accounts list using the filter method in two ways:

get all non-empty accounts (balance > 0) and save it to the variable nonEmptyAccounts
get all non-locked accounts with too much money (balance >= 100 000 000) and save it to the variable accountsWithTooMuchMoney

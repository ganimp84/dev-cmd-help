# Ubuntu

## Open Files

### To find open files count per process

*to print the number of open files, process name and pid*
```bash
sudo lsof | perl -lane '$x{"$F[0]:$F[1]"}++;
END { print "$x{$_}\t$_" for sort {$x{$a}<=>$x{$b}} keys %x}'
```

**Example output:**

```bash
5880    skype:22976
22686   java:23791
```

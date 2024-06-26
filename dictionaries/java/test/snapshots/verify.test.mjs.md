# Snapshot report for `test/verify.test.mjs`

The actual snapshot is saved in `verify.test.mjs.snap`.

Generated by [AVA](https://avajs.dev).

## verify samples/GFG.java against snapshot

> Snapshot 1

    [
      `I _     0-   63 | /*␊
       * Original from [Import Statement in Java - GeeksForGeeks](`,
      'E _    63-  201 | https://www.geeksforgeeks.org/import-statement-in-java/#:~:text=An%20import%20statement%20tells%20the,is%20defined%20under%20a%20package.)',
      `I _   201-  340 | ␊
       */␊
      ␊
      // Java program to demonstrate the␊
      // working of import statement␊
      ␊
      // Importing ArrayList class specified␊
      // under java.util package␊
      `,
      'E _   340-  366 | import java.util.ArrayList',
      `I _   366-  368 | ;␊
      `,
      'E _   368-  389 | import java.util.Date',
      `I _   389-  643 | ;␊
      ␊
      class GFG {␊
      ␊
          // Main method␊
          public static void main(String[] args) {␊
              // Declaring an ArrayList of String type␊
              ArrayList<String> arrayList = new ArrayList<String>();␊
      ␊
              // Adding elements in the ArrayList␊
              arrayList`,
      'E _   643-  647 | .add',
      `I _   647-  675 | ("Geeks");␊
              arrayList`,
      'E _   675-  679 | .add',
      `I _   679-  705 | ("For");␊
              arrayList`,
      'E _   705-  709 | .add',
      `I _   709-  766 | ("Geeks");␊
      ␊
              // Print the ArrayList␊
              System`,
      'E _   766-  778 | .out.println',
      `I _   778-  855 | ("ArrayList: " + arrayList);␊
      ␊
              Date date = new Date();␊
      ␊
              System`,
      'E _   855-  867 | .out.println',
      'I _   867-  883 | ("Date: " + date',
      'E _   883-  892 | .toString',
      `I _   892-  905 | ());␊
          }␊
      }␊
      `,
    ]

## verify samples/pascal_s-triangle/Main.java against snapshot

> Snapshot 1

    [
      `I _     0-   42 | /**␊
       * [Pascal's triangle -␊
       * Wikipedia](`,
      'E _    42-   92 | https://en.wikipedia.org/wiki/Pascal%27s_triangle)',
      `I _    92-  342 | ␊
       */␊
      public class Main {␊
      ␊
          public static void main(String[] args) {␊
              int rows = 5, k = 0, count = 0, count1 = 0;␊
      ␊
              for (int i = 1; i <= rows; ++i) {␊
                  for (int space = 1; space <= rows - i; ++space) {␊
                      System`,
      'E _   342-  352 | .out.print',
      `I _   352-  504 | ("  ");␊
                      ++count;␊
                  }␊
      ␊
                  while (k != 2 * i - 1) {␊
                      if (count <= rows - 1) {␊
                          System`,
      'E _   504-  514 | .out.print',
      `I _   514-  641 | ((i + k) + " ");␊
                          ++count;␊
                      } else {␊
                          ++count1;␊
                          System`,
      'E _   641-  651 | .out.print',
      `I _   651-  790 | ((i + k - 2 * count1) + " ");␊
                      }␊
      ␊
                      ++k;␊
                  }␊
                  count1 = count = k = 0;␊
      ␊
                  System`,
      'E _   790-  802 | .out.println',
      `I _   802-  824 | ();␊
              }␊
          }␊
      }␊
      `,
    ]

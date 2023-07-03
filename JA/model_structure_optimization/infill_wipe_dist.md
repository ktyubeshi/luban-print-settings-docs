インフィル移動距離(Infill Wipe Distance)
====

この設定は、インフィルを印刷し終わった後、ノズルを少し移動させます。この小さな移動の目的は、隣の壁に材料を拭き取ることです。こうすることで、インフィルと壁がよりよく融合します。

This setting will make the nozzle travel a little bit further after it finishes printing an infill line. The aim of this small travel move is to wipe off the material onto the adjacent wall. This fuses the infill line to the wall better.


![A visualisation of infill overlap and wipe distance](../images/infill_overlap.svg)

この移動はオブジェクトを強くする一方で、主な欠点は、この移動が壁を横切り、プリントの外側に目に見える跡を残すことです。事実上、インフィルパターンがシェルからより透けるようになります。

While this travel move makes the object stronger, the main disadvantage is that this travel move will cross the wall and leave a visible mark on the outside of the print. In effect, it makes the infill pattern shine through the shell more.

この設定はインフィルラインの両端にのみ適用されます。連結したインフィルラインを使用する場合、両端はかなり少なくなります。

This setting only applies to the ends of the infill lines. When using connected infill lines, there will be much fewer ends.

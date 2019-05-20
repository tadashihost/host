CODE

<? $act=$HTTP_GET_VARS['act'];
// Starting the server...
if ($act=="start")
{
$output = shell_exec("./samp-server.exe start");
echo $output;
}
// Stopping the server...
elseif ($act=="stop")
{
$output = shell_exec("./samp-server.exe stop");
echo $output;
} ?>

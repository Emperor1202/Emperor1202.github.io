<?PHP
require('fpdf.php');


$pdf->AddPage('P', 'A4');
$pdf->SetAutoPageBreak(true, 10);
$pdf->SetFont('Arial', '', 12);
$pdf->SetTopMargin(10);
$pdf->SetLeftMargin(10);
$pdf->SetRightMargin(10);


/* --- Text --- */
$pdf->SetFont('DejaVu', '', 18);
$pdf->Text(58, 16, 'Ramon Magsaysay Memorial Colleges');
/* --- Text --- */
$pdf->SetFontSize(10);
$pdf->Text(82, 21, 'Pioneer Avenue, General Santos City');
/* --- Text --- */
$pdf->Text(99, 26, '9500 Philippines');
/* --- Text --- */
$pdf->Text(95, 30, 'Tel#:(083) 552-3264');
/* --- Text --- */
$pdf->Text(96, 35, 'Fax:(083) 301-1927');
/* --- Text --- */
$pdf->Text(101, 40, 'P.O.Box: 160');


$pdf->Output('created_pdf.pdf','I');
?>
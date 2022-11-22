-- phpMyAdmin SQL Dump
-- version 4.9.0.1
-- https://www.phpmyadmin.net/
--
-- Host: 127.0.0.1
-- Generation Time: Apr 20, 2020 at 06:01 PM
-- Server version: 10.4.6-MariaDB
-- PHP Version: 7.3.9

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
SET AUTOCOMMIT = 0;
START TRANSACTION;
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- Database: `akademik`
--

-- --------------------------------------------------------

--
-- Table structure for table `mahasiswa`
--

CREATE TABLE `mahasiswa` (
  `Nim` bigint(13) NOT NULL,
  `Nama_Mhs` varchar(255) NOT NULL,
  `Jenis_Kelamin` varchar(255) NOT NULL,
  `alamat` varchar(255) NOT NULL,
  `Program_Studi` varchar(255) NOT NULL,
  `foto` varchar(255)NOT NULL,
  `email` varchar(255) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `mahasiswa`
--

INSERT INTO `mahasiswa` (`Nim`, `Nama_Mhs`, `Jenis_Kelamin`, `alamat` ,`Program_Studi`, `foto`, `email` ) VALUES
(18051214081, 'Arief Luqman', 'Laki-Laki', 'Lidah Kulon Gang 4 Nomer 15', 'Sistem Informasi', 'arif3x4.jpg' , 'arifluqman12@gmail.com' ),
(20050974053, 'Ananda Irvan Tri Kurniawan', 'Laki-Laki', 'Jl. Mutiara 5.1 Nomer 14', 'Pendidikan Teknologi Infomasi', 'ananda3x4.jpg' , 'anandairvan53@gmail.com' ),
(20050974005, 'Shelma Imara Bakir', 'Perempuan', 'Jl.Trosobo Gang 6 Nomer 28', 'Pendidikan Teknologi Infomasi', 'shelma3x4.jpg' , 'shelma05@gmail.com' )
;

--
-- Indexes for dumped tables
--

--
-- Indexes for table `mahasiswa`
--
ALTER TABLE `mahasiswa`
  ADD PRIMARY KEY (`Nim`);
COMMIT;

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;

# ECG_Signal_MATLAB_Code
clc;
clear;
close all;

data = table2array(readtable('ecg.csv'));

for i = 1:140
    plot(data(:,i));
    hold on
end

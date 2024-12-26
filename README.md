# test
test nha-luong
import React from "react";
import DacSacTuNhien from "./DacSacTuNhien";
import CauChuyen from "./CauChuyen";
import SanPhamNoiBat from "./SanPhamNoiBat";
import DanhMuc from "./DanhMuc";
import ChatLuongCamKet from "./ChatLuongCamKet";
import TepChua from "./TepChua";

function NhaLuong() {
  return (
    <div>
      <div className="w-full h-[80px] bg-white flex items-center justify-between px-5 lg:px-24">
        <TepChua />
        <img
          src="/images/logo-nhaluong.png"
          alt="Logo-nhaluong"
          className="h-[40px]"
        />
        <div className=" border-[#125194] hidden lg:block h-10 border-l-[2px] "></div>
        <p className="text-[#125194] hidden lg:block">Trang chủ</p>
        <p className="text-[#8A8A8A] hidden lg:block">Tất cả sản phẩm</p>
        <p className="text-[#8A8A8A] hidden lg:block">Mật ong</p>
        <p className="text-[#8A8A8A] hidden lg:block">Nông sản tự nhiên</p>
        <p className="text-[#8A8A8A] hidden lg:block">Nông sản khác</p>
        <p className="text-[#8A8A8A] hidden lg:block">Combo ưu đãi</p>
        <p className="text-[#8A8A8A] hidden lg:block">Bài viết</p>
        <img
          src="/images/thanhtimkiem.png"
          alt="thanhtimkiem"
          className="h-[24px]"
        />
        <img src="/images/giohang.png" alt="giohang" className="h-[24px]" />
      </div>

      <DacSacTuNhien />
      <CauChuyen />
      <SanPhamNoiBat />
      <DanhMuc />
      <ChatLuongCamKet />
      <div className="bg-white lg:grid grid-cols-5 lg:px-24 p-5 lg:pb-20">
        <div className="flex justify-between items-center">
          <img
            src="/images/logocuanhaluong.png"
            alt="Logocuanhaluong"
            className="h-[296px] hidden sm:flex"
          />
          <img src="/images/logoNhaluong.png" alt="logoNhaluong" />
          <img
            src="/images/bocongthuong.png"
            alt="bocongthuong"
            className="h-[33px]"
          />
        </div>
        <div className="text-[#6D6E76] ">
          <p className="text-[#23262F] w-36 font-bold py-10">
            CÔNG TY TNHH NHÀ LƯƠNG
          </p>
          <div className="space-y-4">
            <p className="text-[#23262F] font-bold">Giấy CNĐKKD: </p>
            <p>5901174113 do Sở Kế </p>
            <p>hoạch và Đầu tư tỉnh </p>
            <p>Gia Lai cấp ngày </p>
            <p>19/07/2021</p>
          </div>
        </div>
        <div className="border-t sm:hidden border-gray-300 my-6"></div>
        <div className="text-[#6D6E76] ">
          <p className="text-[#23262F] font-bold py-10">SẢN PHẨM</p>
          <div className="space-y-4">
            <p>Mật Ong</p>
            <p>Hạt Dinh Dưỡng</p>
            <p>Hạt Dinh Dưỡng</p>
            <p>Hạt Dinh Dưỡng</p>
          </div>
        </div>
        <div className="border-t sm:hidden border-gray-300 my-6"></div>

        <div className="text-[#6D6E76] ">
          <p className="text-[#23262F] font-bold py-10">CÁC CHÍNH SÁCH</p>
          <div className="space-y-4">
            <p>Chính Sách Bán Hàng</p>
            <p>Chính Sách Đổi Trả</p>
            <p>Chính Sách Đại Lý</p>
            <p>Chính Sách Giao Hàng</p>
          </div>
        </div>
        <div className="border-t border-gray-300 sm:hidden my-6"></div>

        <div className="text-[#6D6E76] ">
          <p className="text-[#23262F] font-bold py-10">LIÊN HỆ</p>
          <div className="space-y-4">
            <p>Hotline: 090.756.996</p>
            <p>CN1: 63 Đồng Nhân, Đông La</p>
            <p>Hoài Đức, Hà Nội</p>
          </div>
        </div>
        <div className="border-t border-gray-300 sm:hidden my-6"></div>
      </div>
      <div className="bg-[#FCFCFD] flex pb-5 lg:py-10 justify-around">
        <p className="text-[#777E90]">
          Copyright © 2023 Nhà Lương. All rights reserved
        </p>
        <div className="hidden sm:flex gap-5">
          <img src="/images/facebook.png" alt="facebook" className="h-[24px]" />
          <img src="/images/Twitter.png" alt="Twitter" className="h-[24px]" />
          <img
            src="/images/Instagram.png"
            alt="Instagram"
            className="h-[24px] "
          />
        </div>
      </div>
    </div>
  );
}

export default NhaLuong;

<Type Name="AdlsRuntimeException" FullName="Microsoft.Azure.Management.DataLake.Store.Models.AdlsRuntimeException">
  <TypeSignature Language="C#" Value="public class AdlsRuntimeException : Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdlsRuntimeException extends Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsRuntimeException" />
  <TypeSignature Language="VB.NET" Value="Public Class AdlsRuntimeException&#xA;Inherits AdlsRemoteException" />
  <TypeSignature Language="F#" Value="type AdlsRuntimeException = class&#xA;    inherit AdlsRemoteException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("RuntimeException")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            操作中に予期しないエラーが発生した場合にスロー WebHDFS 例外。 500 のエラー応答コードには、(内部サーバー エラー) が返されるとスローされます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdlsRuntimeException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.AdlsRuntimeException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AdlsRuntimeException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdlsRuntimeException (string javaClassName = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string javaClassName, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.AdlsRuntimeException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional javaClassName As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.AdlsRuntimeException : string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.AdlsRuntimeException" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.AdlsRuntimeException (javaClassName, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="javaClassName" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="javaClassName">フル パッケージのクラス名 'java.lang.IllegalArgumentException' など、スローされる例外。</param>
        <param name="message">など、スローされた例外に関連付けられたメッセージ ' webhdfs パラメーター「アクセス許可」に無効な値:...' です。</param>
        <summary>
            AdlsRuntimeException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
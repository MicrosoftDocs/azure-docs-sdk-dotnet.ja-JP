<Type Name="AdlsFileAlreadyExistsException" FullName="Microsoft.Azure.Management.DataLake.Store.Models.AdlsFileAlreadyExistsException">
  <TypeSignature Language="C#" Value="public class AdlsFileAlreadyExistsException : Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdlsFileAlreadyExistsException extends Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsFileAlreadyExistsException" />
  <TypeSignature Language="VB.NET" Value="Public Class AdlsFileAlreadyExistsException&#xA;Inherits AdlsRemoteException" />
  <TypeSignature Language="F#" Value="type AdlsFileAlreadyExistsException = class&#xA;    inherit AdlsRemoteException" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("FileAlreadyExistsException")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            ファイルまたはフォルダーを既にを示すスロー WebHDFS 例外が存在します。 403 エラー応答コードが返されます (禁止されている) 場合にスローされます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdlsFileAlreadyExistsException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.AdlsFileAlreadyExistsException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AdlsFileAlreadyExistsException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdlsFileAlreadyExistsException (string javaClassName = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string javaClassName, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.AdlsFileAlreadyExistsException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional javaClassName As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.AdlsFileAlreadyExistsException : string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.AdlsFileAlreadyExistsException" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.AdlsFileAlreadyExistsException (javaClassName, message)" />
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
            AdlsFileAlreadyExistsException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
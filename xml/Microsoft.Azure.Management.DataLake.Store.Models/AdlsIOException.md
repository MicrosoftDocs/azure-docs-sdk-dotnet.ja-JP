<Type Name="AdlsIOException" FullName="Microsoft.Azure.Management.DataLake.Store.Models.AdlsIOException">
  <TypeSignature Language="C#" Value="public class AdlsIOException : Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdlsIOException extends Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsIOException" />
  <TypeSignature Language="VB.NET" Value="Public Class AdlsIOException&#xA;Inherits AdlsRemoteException" />
  <TypeSignature Language="F#" Value="type AdlsIOException = class&#xA;    inherit AdlsRemoteException" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("IOException")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="0976f-101">WebHDFS スローされる例外を示すがあるエラーが発生 IO (読み取りまたは書き込み)。</span><span class="sxs-lookup"><span data-stu-id="0976f-101">A WebHDFS exception thrown indicating there was an IO (read or write) error.</span></span> <span data-ttu-id="0976f-102">403 エラー応答コードが返されます (禁止されている) 場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0976f-102">Thrown when a 403 error response code is returned (forbidden).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdlsIOException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.AdlsIOException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0976f-103">AdlsIOException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0976f-103">Initializes a new instance of the AdlsIOException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdlsIOException (string javaClassName = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string javaClassName, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.AdlsIOException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional javaClassName As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.AdlsIOException : string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.AdlsIOException" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.AdlsIOException (javaClassName, message)" />
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
        <param name="javaClassName"><span data-ttu-id="0976f-104">フル パッケージのクラス名 'java.lang.IllegalArgumentException' など、スローされる例外。</span><span class="sxs-lookup"><span data-stu-id="0976f-104">the full class package name for the exception thrown, such as 'java.lang.IllegalArgumentException'.</span></span></param>
        <param name="message"><span data-ttu-id="0976f-105">など、スローされた例外に関連付けられたメッセージ ' webhdfs パラメーター「アクセス許可」に無効な値:...' です。</span><span class="sxs-lookup"><span data-stu-id="0976f-105">the message associated with the exception that was thrown, such as 'Invalid value for webhdfs parameter "permission":...'.</span></span></param>
        <summary>
            <span data-ttu-id="0976f-106">AdlsIOException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0976f-106">Initializes a new instance of the AdlsIOException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
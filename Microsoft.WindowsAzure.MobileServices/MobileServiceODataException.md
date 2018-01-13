<Type Name="MobileServiceODataException" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceODataException">
  <TypeSignature Language="C#" Value="public class MobileServiceODataException : InvalidOperationException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServiceODataException extends System.InvalidOperationException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceODataException" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServiceODataException&#xA;Inherits InvalidOperationException" />
  <TypeSignature Language="F#" Value="type MobileServiceODataException = class&#xA;    inherit InvalidOperationException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.InvalidOperationException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1b20c-101">OData クエリの解析中に例外を表す例外の種類。</span><span class="sxs-lookup"><span data-stu-id="1b20c-101">Exception type representing exceptions in parsing of OData queries.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceODataException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceODataException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="1b20c-102">
          <see cref="T:Microsoft.WindowsAzure.MobileService.MobileServiceODataException" /> クラスの新しいインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="1b20c-102">Creates a new instance of the <see cref="T:Microsoft.WindowsAzure.MobileService.MobileServiceODataException" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceODataException (string message, int errorPos);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, int32 errorPos) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceODataException.#ctor(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorPos As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceODataException : string * int -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceODataException" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceODataException (message, errorPos)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorPos" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="1b20c-103">この例外のプレーンテキスト エラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="1b20c-103">The plain text error message for this exception.</span></span></param>
        <param name="errorPos"><span data-ttu-id="1b20c-104">エラーが存在する文字列内の位置。</span><span class="sxs-lookup"><span data-stu-id="1b20c-104">The position in string where error exists.</span></span></param>
        <summary><span data-ttu-id="1b20c-105">エラー メッセージを使用して、<see cref="T:Microsoft.WindowsAzure.MobileService.MobileServiceODataException" /> クラスの新しいインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="1b20c-105">Creates a new instance of the <see cref="T:Microsoft.WindowsAzure.MobileService.MobileServiceODataException" /> class with an error message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceODataException (string message, int errorPos, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, int32 errorPos, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceODataException.#ctor(System.String,System.Int32,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorPos As Integer, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceODataException : string * int * Exception -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceODataException" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceODataException (message, errorPos, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorPos" Type="System.Int32" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="1b20c-106">この例外のプレーンテキスト エラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="1b20c-106">The plain text error message for this exception.</span></span></param>
        <param name="errorPos"><span data-ttu-id="1b20c-107">エラーが存在する文字列内の位置。</span><span class="sxs-lookup"><span data-stu-id="1b20c-107">The position in string where error exists.</span></span></param>
        <param name="innerException"><span data-ttu-id="1b20c-108">この例外がスローされる原因である内部例外。</span><span class="sxs-lookup"><span data-stu-id="1b20c-108">The inner exception that is the cause of this exception to be thrown.</span></span></param>
        <summary><span data-ttu-id="1b20c-109">エラー メッセージおよび内部例外を使用して、<see cref="T:Microsoft.WindowsAzure.MobileService.MobileServiceODataException" /> クラスの新しいインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="1b20c-109">Creates a new instance of the <see cref="T:Microsoft.WindowsAzure.MobileService.MobileServiceODataException" /> class with an error message and an inner exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorPosition">
      <MemberSignature Language="C#" Value="public int ErrorPosition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ErrorPosition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceODataException.ErrorPosition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorPosition As Integer" />
      <MemberSignature Language="F#" Value="member this.ErrorPosition : int" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceODataException.ErrorPosition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b20c-110">エラーが存在する文字列内の位置</span><span class="sxs-lookup"><span data-stu-id="1b20c-110">The position in string where error exists</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
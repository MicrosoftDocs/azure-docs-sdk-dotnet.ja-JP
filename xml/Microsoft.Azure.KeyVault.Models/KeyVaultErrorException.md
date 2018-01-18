<Type Name="KeyVaultErrorException" FullName="Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
  <TypeSignature Language="C#" Value="public class KeyVaultErrorException : Microsoft.Rest.RestException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyVaultErrorException extends Microsoft.Rest.RestException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyVaultErrorException&#xA;Inherits RestException" />
  <TypeSignature Language="F#" Value="type KeyVaultErrorException = class&#xA;    inherit RestException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.RestException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="92ab4-101">KeyVaultError 情報で無効な応答にスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="92ab4-101">Exception thrown for an invalid response with KeyVaultError information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultErrorException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="92ab4-102">KeyVaultErrorException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="92ab4-102">Initializes a new instance of the KeyVaultErrorException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultErrorException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.KeyVaultErrorException : string -&gt; Microsoft.Azure.KeyVault.Models.KeyVaultErrorException" Usage="new Microsoft.Azure.KeyVault.Models.KeyVaultErrorException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="92ab4-103">例外メッセージ。</span><span class="sxs-lookup"><span data-stu-id="92ab4-103">The exception message.</span></span></param>
        <summary>
            <span data-ttu-id="92ab4-104">KeyVaultErrorException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="92ab4-104">Initializes a new instance of the KeyVaultErrorException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultErrorException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.KeyVaultErrorException : string * Exception -&gt; Microsoft.Azure.KeyVault.Models.KeyVaultErrorException" Usage="new Microsoft.Azure.KeyVault.Models.KeyVaultErrorException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="92ab4-105">例外メッセージ。</span><span class="sxs-lookup"><span data-stu-id="92ab4-105">The exception message.</span></span></param>
        <param name="innerException"><span data-ttu-id="92ab4-106">内部例外。</span><span class="sxs-lookup"><span data-stu-id="92ab4-106">Inner exception.</span></span></param>
        <summary>
            <span data-ttu-id="92ab4-107">KeyVaultErrorException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="92ab4-107">Initializes a new instance of the KeyVaultErrorException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.KeyVaultError Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.KeyVaultError Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As KeyVaultError" />
      <MemberSignature Language="F#" Value="member this.Body : Microsoft.Azure.KeyVault.Models.KeyVaultError with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyVaultErrorException.Body" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.KeyVaultError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92ab4-108">取得または body オブジェクトを設定します。</span><span class="sxs-lookup"><span data-stu-id="92ab4-108">Gets or sets the body object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public override string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException.Message" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.KeyVault.Models.KeyVaultErrorException.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92ab4-109">サービス メッセージを返す場合は、それ以外の場合、メッセージを返します全般</span><span class="sxs-lookup"><span data-stu-id="92ab4-109">Return the service message if available, otherwise returns the general message</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Request">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.HttpRequestMessageWrapper Request { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.HttpRequestMessageWrapper Request" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException.Request" />
      <MemberSignature Language="VB.NET" Value="Public Property Request As HttpRequestMessageWrapper" />
      <MemberSignature Language="F#" Value="member this.Request : Microsoft.Rest.HttpRequestMessageWrapper with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyVaultErrorException.Request" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.HttpRequestMessageWrapper</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92ab4-110">関連付けられている HTTP 要求に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="92ab4-110">Gets information about the associated HTTP request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Response">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.HttpResponseMessageWrapper Response { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.HttpResponseMessageWrapper Response" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException.Response" />
      <MemberSignature Language="VB.NET" Value="Public Property Response As HttpResponseMessageWrapper" />
      <MemberSignature Language="F#" Value="member this.Response : Microsoft.Rest.HttpResponseMessageWrapper with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyVaultErrorException.Response" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.HttpResponseMessageWrapper</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92ab4-111">関連付けられている HTTP 応答に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="92ab4-111">Gets information about the associated HTTP response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
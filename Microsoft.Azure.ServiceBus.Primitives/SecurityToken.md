<Type Name="SecurityToken" FullName="Microsoft.Azure.ServiceBus.Primitives.SecurityToken">
  <TypeSignature Language="C#" Value="public class SecurityToken" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecurityToken extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Primitives.SecurityToken" />
  <TypeSignature Language="VB.NET" Value="Public Class SecurityToken" />
  <TypeSignature Language="F#" Value="type SecurityToken = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3c959-101">対象者、期限、および文字列のトークン値などのセキュリティ トークンに関する情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="3c959-101">Provides information about a security token such as audience, expiry time, and the string token value.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityToken (string tokenString, DateTime expiresAtUtc, string audience, string tokenType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tokenString, valuetype System.DateTime expiresAtUtc, string audience, string tokenType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.SecurityToken.#ctor(System.String,System.DateTime,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tokenString As String, expiresAtUtc As DateTime, audience As String, tokenType As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.Primitives.SecurityToken : string * DateTime * string * string -&gt; Microsoft.Azure.ServiceBus.Primitives.SecurityToken" Usage="new Microsoft.Azure.ServiceBus.Primitives.SecurityToken (tokenString, expiresAtUtc, audience, tokenType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenString" Type="System.String" />
        <Parameter Name="expiresAtUtc" Type="System.DateTime" />
        <Parameter Name="audience" Type="System.String" />
        <Parameter Name="tokenType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tokenString"><span data-ttu-id="3c959-102">トークン</span><span class="sxs-lookup"><span data-stu-id="3c959-102">The token</span></span></param>
        <param name="expiresAtUtc"><span data-ttu-id="3c959-103">有効期限</span><span class="sxs-lookup"><span data-stu-id="3c959-103">The expiration time</span></span></param>
        <param name="audience"><span data-ttu-id="3c959-104">対象ユーザー</span><span class="sxs-lookup"><span data-stu-id="3c959-104">The audience</span></span></param>
        <param name="tokenType"><span data-ttu-id="3c959-105">トークンの種類</span><span class="sxs-lookup"><span data-stu-id="3c959-105">The type of the token</span></span></param>
        <summary>
            <span data-ttu-id="3c959-106">
                      <see cref="T:Microsoft.Azure.ServiceBus.Primitives.SecurityToken" /> クラスの新しいインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="3c959-106">Creates a new instance of the <see cref="T:Microsoft.Azure.ServiceBus.Primitives.SecurityToken" /> class.</span></span>
</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Audience">
      <MemberSignature Language="C#" Value="public string Audience { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Audience" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Primitives.SecurityToken.Audience" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Audience As String" />
      <MemberSignature Language="F#" Value="member this.Audience : string" Usage="Microsoft.Azure.ServiceBus.Primitives.SecurityToken.Audience" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c959-107">このトークンの対象ユーザーを取得します。</span><span class="sxs-lookup"><span data-stu-id="3c959-107">Gets the audience of this token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiresAtUtc">
      <MemberSignature Language="C#" Value="public DateTime ExpiresAtUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiresAtUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Primitives.SecurityToken.ExpiresAtUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresAtUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiresAtUtc : DateTime" Usage="Microsoft.Azure.ServiceBus.Primitives.SecurityToken.ExpiresAtUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c959-108">このトークンの有効期限を取得します。</span><span class="sxs-lookup"><span data-stu-id="3c959-108">Gets the expiration time of this token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenType">
      <MemberSignature Language="C#" Value="public virtual string TokenType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Primitives.SecurityToken.TokenType" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property TokenType As String" />
      <MemberSignature Language="F#" Value="member this.TokenType : string" Usage="Microsoft.Azure.ServiceBus.Primitives.SecurityToken.TokenType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c959-109">トークンの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="3c959-109">Gets the token type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenValue">
      <MemberSignature Language="C#" Value="public virtual string TokenValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Primitives.SecurityToken.TokenValue" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property TokenValue As String" />
      <MemberSignature Language="F#" Value="member this.TokenValue : string" Usage="Microsoft.Azure.ServiceBus.Primitives.SecurityToken.TokenValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c959-110">実際のトークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="3c959-110">Gets the actual token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
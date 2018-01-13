<Type Name="SecurityToken" FullName="Microsoft.Azure.EventHubs.SecurityToken">
  <TypeSignature Language="C#" Value="public class SecurityToken" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecurityToken extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.SecurityToken" />
  <TypeSignature Language="VB.NET" Value="Public Class SecurityToken" />
  <TypeSignature Language="F#" Value="type SecurityToken = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3fe75-101">対象者、期限、および文字列のトークン値などのセキュリティ トークンに関する情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="3fe75-101">Provides information about a security token such as audience, expiry time, and the string token value.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityToken (string tokenString, DateTime expiresAtUtc, string audience, string tokenType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tokenString, valuetype System.DateTime expiresAtUtc, string audience, string tokenType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.SecurityToken.#ctor(System.String,System.DateTime,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tokenString As String, expiresAtUtc As DateTime, audience As String, tokenType As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.SecurityToken : string * DateTime * string * string -&gt; Microsoft.Azure.EventHubs.SecurityToken" Usage="new Microsoft.Azure.EventHubs.SecurityToken (tokenString, expiresAtUtc, audience, tokenType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenString" Type="System.String" />
        <Parameter Name="expiresAtUtc" Type="System.DateTime" />
        <Parameter Name="audience" Type="System.String" />
        <Parameter Name="tokenType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tokenString"><span data-ttu-id="3fe75-102">トークン</span><span class="sxs-lookup"><span data-stu-id="3fe75-102">The token</span></span></param>
        <param name="expiresAtUtc"><span data-ttu-id="3fe75-103">有効期限</span><span class="sxs-lookup"><span data-stu-id="3fe75-103">The expiration time</span></span></param>
        <param name="audience"><span data-ttu-id="3fe75-104">対象ユーザー</span><span class="sxs-lookup"><span data-stu-id="3fe75-104">The audience</span></span></param>
        <param name="tokenType"><span data-ttu-id="3fe75-105">トークンの種類</span><span class="sxs-lookup"><span data-stu-id="3fe75-105">The type of the token</span></span></param>
        <summary>
            <span data-ttu-id="3fe75-106">
                      <see cref="T:Microsoft.Azure.EventHubs.SecurityToken" /> クラスの新しいインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="3fe75-106">Creates a new instance of the <see cref="T:Microsoft.Azure.EventHubs.SecurityToken" /> class.</span></span>
</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Audience">
      <MemberSignature Language="C#" Value="public string Audience { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Audience" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.SecurityToken.Audience" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Audience As String" />
      <MemberSignature Language="F#" Value="member this.Audience : string" Usage="Microsoft.Azure.EventHubs.SecurityToken.Audience" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fe75-107">このトークンの対象ユーザーを取得します。</span><span class="sxs-lookup"><span data-stu-id="3fe75-107">Gets the audience of this token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiresAtUtc">
      <MemberSignature Language="C#" Value="public DateTime ExpiresAtUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiresAtUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.SecurityToken.ExpiresAtUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresAtUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiresAtUtc : DateTime" Usage="Microsoft.Azure.EventHubs.SecurityToken.ExpiresAtUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fe75-108">このトークンの有効期限を取得します。</span><span class="sxs-lookup"><span data-stu-id="3fe75-108">Gets the expiration time of this token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenType">
      <MemberSignature Language="C#" Value="public virtual string TokenType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.SecurityToken.TokenType" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property TokenType As String" />
      <MemberSignature Language="F#" Value="member this.TokenType : string" Usage="Microsoft.Azure.EventHubs.SecurityToken.TokenType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fe75-109">トークンの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="3fe75-109">Gets the token type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenValue">
      <MemberSignature Language="C#" Value="public virtual string TokenValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.SecurityToken.TokenValue" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property TokenValue As String" />
      <MemberSignature Language="F#" Value="member this.TokenValue : string" Usage="Microsoft.Azure.EventHubs.SecurityToken.TokenValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fe75-110">実際のトークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="3fe75-110">Gets the actual token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="ValidateCustomDomainOutputInner" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner">
  <TypeSignature Language="C#" Value="public class ValidateCustomDomainOutputInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ValidateCustomDomainOutputInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ValidateCustomDomainOutputInner" />
  <TypeSignature Language="F#" Value="type ValidateCustomDomainOutputInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f17e4-101">カスタム ドメインの検証の出力です。</span><span class="sxs-lookup"><span data-stu-id="f17e4-101">Output of custom domain validation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ValidateCustomDomainOutputInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f17e4-102">ValidateCustomDomainOutputInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f17e4-102">Initializes a new instance of the ValidateCustomDomainOutputInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ValidateCustomDomainOutputInner (Nullable&lt;bool&gt; customDomainValidated = null, string reason = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; customDomainValidated, string reason, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner.#ctor(System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional customDomainValidated As Nullable(Of Boolean) = null, Optional reason As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner : Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner (customDomainValidated, reason, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="customDomainValidated" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="reason" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="customDomainValidated"><span data-ttu-id="f17e4-103">カスタム ドメインを検証するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="f17e4-103">Indicates whether the custom domain is validated or not.</span></span></param>
        <param name="reason"><span data-ttu-id="f17e4-104">カスタム ドメインが有効な理由です。</span><span class="sxs-lookup"><span data-stu-id="f17e4-104">The reason why the custom domain is not valid.</span></span></param>
        <param name="message"><span data-ttu-id="f17e4-105">カスタム ドメインが有効な理由を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="f17e4-105">Error message describing why the custom domain is not valid.</span></span></param>
        <summary>
            <span data-ttu-id="f17e4-106">ValidateCustomDomainOutputInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f17e4-106">Initializes a new instance of the ValidateCustomDomainOutputInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomDomainValidated">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CustomDomainValidated { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CustomDomainValidated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner.CustomDomainValidated" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomDomainValidated As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CustomDomainValidated : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner.CustomDomainValidated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="customDomainValidated")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f17e4-107">取得または設定は、カスタム ドメインを検証するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="f17e4-107">Gets or sets indicates whether the custom domain is validated or not.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f17e4-108">取得またはカスタムのドメインが有効な理由を説明するエラー メッセージを設定します。</span><span class="sxs-lookup"><span data-stu-id="f17e4-108">Gets or sets error message describing why the custom domain is not valid.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public string Reason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner.Reason" />
      <MemberSignature Language="VB.NET" Value="Public Property Reason As String" />
      <MemberSignature Language="F#" Value="member this.Reason : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f17e4-109">取得またはカスタムのドメインが有効な理由を設定します。</span><span class="sxs-lookup"><span data-stu-id="f17e4-109">Gets or sets the reason why the custom domain is not valid.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
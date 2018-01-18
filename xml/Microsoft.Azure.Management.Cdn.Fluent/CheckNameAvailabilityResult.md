<Type Name="CheckNameAvailabilityResult" FullName="Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult">
  <TypeSignature Language="C#" Value="public class CheckNameAvailabilityResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CheckNameAvailabilityResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckNameAvailabilityResult" />
  <TypeSignature Language="F#" Value="type CheckNameAvailabilityResult = class" />
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
             <span data-ttu-id="fad8c-101">カスタム ドメインの検証の結果です。</span><span class="sxs-lookup"><span data-stu-id="fad8c-101">Result of the custom domain validation.</span></span>
             </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityResult (Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult.#ctor(Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (inner As CheckNameAvailabilityOutputInner)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult : Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner -&gt; Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult" Usage="new Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult inner" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="inner" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner" />
      </Parameters>
      <Docs>
        <param name="inner"><span data-ttu-id="fad8c-102">CheckNameAvailability 要求に対するサーバー応答します。</span><span class="sxs-lookup"><span data-stu-id="fad8c-102">Server response for CheckNameAvailability request.</span></span></param>
        <summary>
             <span data-ttu-id="fad8c-103">サーバー応答オブジェクトから CheckNameAvailabilityResult オブジェクトを構築します。</span><span class="sxs-lookup"><span data-stu-id="fad8c-103">Construct CheckNameAvailabilityResult object from server response object.</span></span>
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fad8c-104">メッセージの値を取得します。</span><span class="sxs-lookup"><span data-stu-id="fad8c-104">Get the message value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="fad8c-105">メッセージの値。</span><span class="sxs-lookup"><span data-stu-id="fad8c-105">The message value.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="NameAvailable">
      <MemberSignature Language="C#" Value="public bool NameAvailable { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool NameAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult.NameAvailable" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NameAvailable As Boolean" />
      <MemberSignature Language="F#" Value="member this.NameAvailable : bool" Usage="Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult.NameAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fad8c-106">名前が使用できるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="fad8c-106">Indicates whether the name is available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="fad8c-107">NameAvailable 値です。</span><span class="sxs-lookup"><span data-stu-id="fad8c-107">The nameAvailable value.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public string Reason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult.Reason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Reason As String" />
      <MemberSignature Language="F#" Value="member this.Reason : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fad8c-108">理由の値を取得します。</span><span class="sxs-lookup"><span data-stu-id="fad8c-108">Get the reason value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="fad8c-109">理由の値。</span><span class="sxs-lookup"><span data-stu-id="fad8c-109">The reason value.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>
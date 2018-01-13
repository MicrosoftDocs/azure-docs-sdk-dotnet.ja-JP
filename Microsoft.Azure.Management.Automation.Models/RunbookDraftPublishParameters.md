<Type Name="RunbookDraftPublishParameters" FullName="Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters">
  <TypeSignature Language="C#" Value="public class RunbookDraftPublishParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RunbookDraftPublishParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class RunbookDraftPublishParameters" />
  <TypeSignature Language="F#" Value="type RunbookDraftPublishParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b0079-101">Runbook の発行操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b0079-101">The parameters supplied to the publish runbook operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RunbookDraftPublishParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b0079-102">RunbookDraftPublishParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b0079-102">Initializes a new instance of the RunbookDraftPublishParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RunbookDraftPublishParameters (string name, string publishedBy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string publishedBy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, publishedBy As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters : string * string -&gt; Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters" Usage="new Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters (name, publishedBy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="publishedBy" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="publishedBy">To be added.</param>
        <summary>
            <span data-ttu-id="b0079-103">必須の引数で RunbookDraftPublishParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b0079-103">Initializes a new instance of the RunbookDraftPublishParameters class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b0079-104">必須。</span><span class="sxs-lookup"><span data-stu-id="b0079-104">Required.</span></span> <span data-ttu-id="b0079-105">取得または runbook 名を設定します。</span><span class="sxs-lookup"><span data-stu-id="b0079-105">Gets or sets the runbook name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishedBy">
      <MemberSignature Language="C#" Value="public string PublishedBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublishedBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters.PublishedBy" />
      <MemberSignature Language="VB.NET" Value="Public Property PublishedBy As String" />
      <MemberSignature Language="F#" Value="member this.PublishedBy : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters.PublishedBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b0079-106">必須。</span><span class="sxs-lookup"><span data-stu-id="b0079-106">Required.</span></span> <span data-ttu-id="b0079-107">取得または設定 id を使用して、公開されています。</span><span class="sxs-lookup"><span data-stu-id="b0079-107">Gets or sets the published by identity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="JobsListOutputFilesOptions" FullName="Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions">
  <TypeSignature Language="C#" Value="public class JobsListOutputFilesOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobsListOutputFilesOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class JobsListOutputFilesOptions" />
  <TypeSignature Language="F#" Value="type JobsListOutputFilesOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1592d-101">ListOutputFiles 操作に追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="1592d-101">Additional parameters for ListOutputFiles operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobsListOutputFilesOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1592d-102">JobsListOutputFilesOptions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1592d-102">Initializes a new instance of the JobsListOutputFilesOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobsListOutputFilesOptions (string outputdirectoryid, Nullable&lt;int&gt; linkexpiryinminutes = null, Nullable&lt;int&gt; maxResults = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string outputdirectoryid, valuetype System.Nullable`1&lt;int32&gt; linkexpiryinminutes, valuetype System.Nullable`1&lt;int32&gt; maxResults) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (outputdirectoryid As String, Optional linkexpiryinminutes As Nullable(Of Integer) = null, Optional maxResults As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions" Usage="new Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions (outputdirectoryid, linkexpiryinminutes, maxResults)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="outputdirectoryid" Type="System.String" />
        <Parameter Name="linkexpiryinminutes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="outputdirectoryid"><span data-ttu-id="1592d-103">ジョブの id は、ディレクトリを出力します。</span><span class="sxs-lookup"><span data-stu-id="1592d-103">Id of the job output directory.</span></span>
            <span data-ttu-id="1592d-104">これは、OutputDirectory--&gt;ジョブの作成中に、ユーザーによって指定された id パラメーター。</span><span class="sxs-lookup"><span data-stu-id="1592d-104">This is the OutputDirectory--&gt;id parameter that is given by the user during Create Job.</span></span></param>
        <param name="linkexpiryinminutes"><span data-ttu-id="1592d-105">(分) のダウンロードのリンクは期限切れの数。</span><span class="sxs-lookup"><span data-stu-id="1592d-105">The number of minutes after which the download link will expire.</span></span></param>
        <param name="maxResults"><span data-ttu-id="1592d-106">応答で返されるアイテムの最大数。</span><span class="sxs-lookup"><span data-stu-id="1592d-106">The maximum number of items to return in the response.</span></span> <span data-ttu-id="1592d-107">最大で 1000 のファイルが返されます。</span><span class="sxs-lookup"><span data-stu-id="1592d-107">A maximum of 1000 files can be returned.</span></span></param>
        <summary>
            <span data-ttu-id="1592d-108">JobsListOutputFilesOptions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1592d-108">Initializes a new instance of the JobsListOutputFilesOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Linkexpiryinminutes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Linkexpiryinminutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Linkexpiryinminutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.Linkexpiryinminutes" />
      <MemberSignature Language="VB.NET" Value="Public Property Linkexpiryinminutes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Linkexpiryinminutes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.Linkexpiryinminutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1592d-109">取得または分のダウンロードのリンクは期限切れの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="1592d-109">Gets or sets the number of minutes after which the download link will expire.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxResults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxResults As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxResults : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.MaxResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1592d-110">取得または応答で返されるアイテムの最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="1592d-110">Gets or sets the maximum number of items to return in the response.</span></span>
            <span data-ttu-id="1592d-111">最大で 1000 のファイルが返されます。</span><span class="sxs-lookup"><span data-stu-id="1592d-111">A maximum of 1000 files can be returned.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Outputdirectoryid">
      <MemberSignature Language="C#" Value="public string Outputdirectoryid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Outputdirectoryid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.Outputdirectoryid" />
      <MemberSignature Language="VB.NET" Value="Public Property Outputdirectoryid As String" />
      <MemberSignature Language="F#" Value="member this.Outputdirectoryid : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.Outputdirectoryid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1592d-112">取得またはジョブの出力ディレクトリの id を設定します。</span><span class="sxs-lookup"><span data-stu-id="1592d-112">Gets or sets id of the job output directory.</span></span> <span data-ttu-id="1592d-113">これは、OutputDirectory--&amp;gt; ジョブの作成中に、ユーザーによって指定された id パラメーター。</span><span class="sxs-lookup"><span data-stu-id="1592d-113">This is the OutputDirectory--&amp;gt;id parameter that is given by the user during Create Job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobsListOutputFilesOptions.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1592d-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="1592d-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1592d-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1592d-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="CoreSummary" FullName="Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary">
  <TypeSignature Language="C#" Value="public class CoreSummary" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CoreSummary extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary" />
  <TypeSignature Language="VB.NET" Value="Public Class CoreSummary" />
  <TypeSignature Language="F#" Value="type CoreSummary = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0d4f6-101">検索の中核となる概要。</span><span class="sxs-lookup"><span data-stu-id="0d4f6-101">The core summary of a search.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CoreSummary ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0d4f6-102">CoreSummary クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0d4f6-102">Initializes a new instance of the CoreSummary class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CoreSummary (long numberOfDocuments, string status = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 numberOfDocuments, string status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary.#ctor(System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (numberOfDocuments As Long, Optional status As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary : int64 * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary (numberOfDocuments, status)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="numberOfDocuments" Type="System.Int64" />
        <Parameter Name="status" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="numberOfDocuments"><span data-ttu-id="0d4f6-103">概要のコアのドキュメントの数。</span><span class="sxs-lookup"><span data-stu-id="0d4f6-103">The number of documents of a core summary.</span></span></param>
        <param name="status"><span data-ttu-id="0d4f6-104">コアのサマリーの状態です。</span><span class="sxs-lookup"><span data-stu-id="0d4f6-104">The status of a core summary.</span></span></param>
        <summary>
            <span data-ttu-id="0d4f6-105">CoreSummary クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0d4f6-105">Initializes a new instance of the CoreSummary class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfDocuments">
      <MemberSignature Language="C#" Value="public long NumberOfDocuments { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NumberOfDocuments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary.NumberOfDocuments" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberOfDocuments As Long" />
      <MemberSignature Language="F#" Value="member this.NumberOfDocuments : int64 with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary.NumberOfDocuments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="NumberOfDocuments")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d4f6-106">取得または設定の主要なドキュメントの数を集計します。</span><span class="sxs-lookup"><span data-stu-id="0d4f6-106">Gets or sets the number of documents of a core summary.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d4f6-107">取得または設定の主要な状態を集計します。</span><span class="sxs-lookup"><span data-stu-id="0d4f6-107">Gets or sets the status of a core summary.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="coreSummary.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0d4f6-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="0d4f6-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0d4f6-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0d4f6-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
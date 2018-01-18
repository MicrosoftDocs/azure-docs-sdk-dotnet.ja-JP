<Type Name="IndexerListResult" FullName="Microsoft.Azure.Search.Models.IndexerListResult">
  <TypeSignature Language="C#" Value="public class IndexerListResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IndexerListResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexerListResult" />
  <TypeSignature Language="VB.NET" Value="Public Class IndexerListResult" />
  <TypeSignature Language="F#" Value="type IndexerListResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7bd9e-101">インデクサーの一覧の要求から応答します。</span><span class="sxs-lookup"><span data-stu-id="7bd9e-101">Response from a List Indexers request.</span></span> <span data-ttu-id="7bd9e-102">成功した場合は、すべてのインデクサーの完全定義が含まれます。</span><span class="sxs-lookup"><span data-stu-id="7bd9e-102">If successful, it includes the full definitions of all indexers.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexerListResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexerListResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7bd9e-103">IndexerListResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7bd9e-103">Initializes a new instance of the IndexerListResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexerListResult (System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Indexer&gt; indexers = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.Indexer&gt; indexers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexerListResult.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Search.Models.Indexer})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional indexers As IList(Of Indexer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.IndexerListResult : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Indexer&gt; -&gt; Microsoft.Azure.Search.Models.IndexerListResult" Usage="new Microsoft.Azure.Search.Models.IndexerListResult indexers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="indexers" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Indexer&gt;" />
      </Parameters>
      <Docs>
        <param name="indexers"><span data-ttu-id="7bd9e-104">Search サービスのインデクサーです。</span><span class="sxs-lookup"><span data-stu-id="7bd9e-104">The indexers in the Search service.</span></span></param>
        <summary>
            <span data-ttu-id="7bd9e-105">IndexerListResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7bd9e-105">Initializes a new instance of the IndexerListResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Indexers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Indexer&gt; Indexers { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.Indexer&gt; Indexers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexerListResult.Indexers" />
      <MemberSignature Language="VB.NET" Value="Public Property Indexers As IList(Of Indexer)" />
      <MemberSignature Language="F#" Value="member this.Indexers : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Indexer&gt; with get, set" Usage="Microsoft.Azure.Search.Models.IndexerListResult.Indexers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Indexer&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7bd9e-106">Search サービスでインデクサーを取得します。</span><span class="sxs-lookup"><span data-stu-id="7bd9e-106">Gets the indexers in the Search service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
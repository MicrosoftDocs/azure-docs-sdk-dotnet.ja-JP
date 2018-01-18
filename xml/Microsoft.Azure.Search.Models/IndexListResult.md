<Type Name="IndexListResult" FullName="Microsoft.Azure.Search.Models.IndexListResult">
  <TypeSignature Language="C#" Value="public class IndexListResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IndexListResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexListResult" />
  <TypeSignature Language="VB.NET" Value="Public Class IndexListResult" />
  <TypeSignature Language="F#" Value="type IndexListResult = class" />
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
            <span data-ttu-id="030a2-101">インデックスの一覧の要求から応答します。</span><span class="sxs-lookup"><span data-stu-id="030a2-101">Response from a List Indexes request.</span></span> <span data-ttu-id="030a2-102">成功した場合は、すべてのインデックスの完全定義が含まれます。</span><span class="sxs-lookup"><span data-stu-id="030a2-102">If successful, it includes the full definitions of all indexes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexListResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexListResult.#ctor" />
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
            <span data-ttu-id="030a2-103">IndexListResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="030a2-103">Initializes a new instance of the IndexListResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexListResult (System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Index&gt; indexes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.Index&gt; indexes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexListResult.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Search.Models.Index})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional indexes As IList(Of Index) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.IndexListResult : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Index&gt; -&gt; Microsoft.Azure.Search.Models.IndexListResult" Usage="new Microsoft.Azure.Search.Models.IndexListResult indexes" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="indexes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Index&gt;" />
      </Parameters>
      <Docs>
        <param name="indexes"><span data-ttu-id="030a2-104">Search サービス内のインデックス。</span><span class="sxs-lookup"><span data-stu-id="030a2-104">The indexes in the Search service.</span></span></param>
        <summary>
            <span data-ttu-id="030a2-105">IndexListResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="030a2-105">Initializes a new instance of the IndexListResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Indexes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Index&gt; Indexes { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.Index&gt; Indexes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexListResult.Indexes" />
      <MemberSignature Language="VB.NET" Value="Public Property Indexes As IList(Of Index)" />
      <MemberSignature Language="F#" Value="member this.Indexes : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Index&gt; with get, set" Usage="Microsoft.Azure.Search.Models.IndexListResult.Indexes" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Index&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="030a2-106">Search サービスでインデックスを取得します。</span><span class="sxs-lookup"><span data-stu-id="030a2-106">Gets the indexes in the Search service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
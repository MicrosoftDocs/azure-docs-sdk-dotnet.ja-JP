<Type Name="SynonymMapListResult" FullName="Microsoft.Azure.Search.Models.SynonymMapListResult">
  <TypeSignature Language="C#" Value="public class SynonymMapListResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SynonymMapListResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SynonymMapListResult" />
  <TypeSignature Language="VB.NET" Value="Public Class SynonymMapListResult" />
  <TypeSignature Language="F#" Value="type SynonymMapListResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cc887-101">リスト SynonymMaps 要求から応答します。</span><span class="sxs-lookup"><span data-stu-id="cc887-101">Response from a List SynonymMaps request.</span></span> <span data-ttu-id="cc887-102">成功した場合は、すべてのシノニム マップの完全定義が含まれます。</span><span class="sxs-lookup"><span data-stu-id="cc887-102">If successful, it includes the full definitions of all synonym maps.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SynonymMapListResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SynonymMapListResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cc887-103">SynonymMapListResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cc887-103">Initializes a new instance of the SynonymMapListResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SynonymMapListResult (System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.SynonymMap&gt; synonymMaps = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.SynonymMap&gt; synonymMaps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SynonymMapListResult.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Search.Models.SynonymMap})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional synonymMaps As IList(Of SynonymMap) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.SynonymMapListResult : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.SynonymMap&gt; -&gt; Microsoft.Azure.Search.Models.SynonymMapListResult" Usage="new Microsoft.Azure.Search.Models.SynonymMapListResult synonymMaps" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="synonymMaps" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;" />
      </Parameters>
      <Docs>
        <param name="synonymMaps"><span data-ttu-id="cc887-104">シノニムは、Search サービスにマップされます。</span><span class="sxs-lookup"><span data-stu-id="cc887-104">The synonym maps in the Search service.</span></span></param>
        <summary>
            <span data-ttu-id="cc887-105">SynonymMapListResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cc887-105">Initializes a new instance of the SynonymMapListResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SynonymMaps">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.SynonymMap&gt; SynonymMaps { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.SynonymMap&gt; SynonymMaps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SynonymMapListResult.SynonymMaps" />
      <MemberSignature Language="VB.NET" Value="Public Property SynonymMaps As IList(Of SynonymMap)" />
      <MemberSignature Language="F#" Value="member this.SynonymMaps : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.SynonymMap&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SynonymMapListResult.SynonymMaps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc887-106">Search サービスでは、シノニム マップを取得します。</span><span class="sxs-lookup"><span data-stu-id="cc887-106">Gets the synonym maps in the Search service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
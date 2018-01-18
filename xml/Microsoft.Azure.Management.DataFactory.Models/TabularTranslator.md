<Type Name="TabularTranslator" FullName="Microsoft.Azure.Management.DataFactory.Models.TabularTranslator">
  <TypeSignature Language="C#" Value="public class TabularTranslator : Microsoft.Azure.Management.DataFactory.Models.CopyTranslator" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TabularTranslator extends Microsoft.Azure.Management.DataFactory.Models.CopyTranslator" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.TabularTranslator" />
  <TypeSignature Language="VB.NET" Value="Public Class TabularTranslator&#xA;Inherits CopyTranslator" />
  <TypeSignature Language="F#" Value="type TabularTranslator = class&#xA;    inherit CopyTranslator" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.CopyTranslator</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b93f7-101">コピー アクティビティ テーブル トランスレーターです。</span><span class="sxs-lookup"><span data-stu-id="b93f7-101">A copy activity tabular translator.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TabularTranslator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TabularTranslator.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b93f7-102">TabularTranslator クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b93f7-102">Initializes a new instance of the TabularTranslator class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TabularTranslator (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object columnMappings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object columnMappings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TabularTranslator.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional columnMappings As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.TabularTranslator : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.TabularTranslator" Usage="new Microsoft.Azure.Management.DataFactory.Models.TabularTranslator (additionalProperties, columnMappings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="columnMappings" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="b93f7-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="b93f7-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="columnMappings"><span data-ttu-id="b93f7-104">列のマッピング。</span><span class="sxs-lookup"><span data-stu-id="b93f7-104">Column mappings.</span></span> <span data-ttu-id="b93f7-105">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="b93f7-105">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="b93f7-106">TabularTranslator クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b93f7-106">Initializes a new instance of the TabularTranslator class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ColumnMappings">
      <MemberSignature Language="C#" Value="public object ColumnMappings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ColumnMappings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TabularTranslator.ColumnMappings" />
      <MemberSignature Language="VB.NET" Value="Public Property ColumnMappings As Object" />
      <MemberSignature Language="F#" Value="member this.ColumnMappings : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TabularTranslator.ColumnMappings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="columnMappings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b93f7-107">取得または列のマッピングを設定します。</span><span class="sxs-lookup"><span data-stu-id="b93f7-107">Gets or sets column mappings.</span></span> <span data-ttu-id="b93f7-108">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="b93f7-108">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
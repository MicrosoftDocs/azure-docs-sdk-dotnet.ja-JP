<Type Name="OperationListResponse" FullName="Microsoft.Azure.Management.DataFactory.Models.OperationListResponse">
  <TypeSignature Language="C#" Value="public class OperationListResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationListResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.OperationListResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationListResponse" />
  <TypeSignature Language="F#" Value="type OperationListResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9946e-101">Data Factory サービスで実行できる操作の一覧。</span><span class="sxs-lookup"><span data-stu-id="9946e-101">A list of operations that can be performed by the Data Factory service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationListResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.OperationListResponse.#ctor" />
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
            <span data-ttu-id="9946e-102">OperationListResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9946e-102">Initializes a new instance of the OperationListResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationListResponse (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Operation&gt; value = null, string nextLink = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Operation&gt; value, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.OperationListResponse.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.Operation},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional value As IList(Of Operation) = null, Optional nextLink As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.OperationListResponse : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Operation&gt; * string -&gt; Microsoft.Azure.Management.DataFactory.Models.OperationListResponse" Usage="new Microsoft.Azure.Management.DataFactory.Models.OperationListResponse (value, nextLink)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Operation&gt;" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="9946e-103">データ ファクトリのリソース プロバイダーでサポートされる Data Factory 操作の一覧です。</span><span class="sxs-lookup"><span data-stu-id="9946e-103">List of Data Factory operations supported by the Data Factory resource provider.</span></span></param>
        <param name="nextLink"><span data-ttu-id="9946e-104">任意の残りの結果が存在しない場合、結果の次のページへのリンク。</span><span class="sxs-lookup"><span data-stu-id="9946e-104">The link to the next page of results, if any remaining results exist.</span></span></param>
        <summary>
            <span data-ttu-id="9946e-105">OperationListResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9946e-105">Initializes a new instance of the OperationListResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextLink">
      <MemberSignature Language="C#" Value="public string NextLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationListResponse.NextLink" />
      <MemberSignature Language="VB.NET" Value="Public Property NextLink As String" />
      <MemberSignature Language="F#" Value="member this.NextLink : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationListResponse.NextLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9946e-106">取得またはの残りの結果が存在しない場合、結果の次のページにリンクを設定します。</span><span class="sxs-lookup"><span data-stu-id="9946e-106">Gets or sets the link to the next page of results, if any remaining results exist.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Operation&gt; Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Operation&gt; Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationListResponse.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As IList(Of Operation)" />
      <MemberSignature Language="F#" Value="member this.Value : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Operation&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationListResponse.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Operation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9946e-107">取得またはデータ ファクトリのリソース プロバイダーでサポートされる Data Factory 操作の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="9946e-107">Gets or sets list of Data Factory operations supported by the Data Factory resource provider.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
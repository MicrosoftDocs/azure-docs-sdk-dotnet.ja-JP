<Type Name="AzureMachineLearningWebServiceInputs" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs">
  <TypeSignature Language="C#" Value="public class AzureMachineLearningWebServiceInputs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMachineLearningWebServiceInputs extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMachineLearningWebServiceInputs" />
  <TypeSignature Language="F#" Value="type AzureMachineLearningWebServiceInputs = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d1d2f-101">Azure Machine Learning web サービスのエンドポイントを入力します。</span><span class="sxs-lookup"><span data-stu-id="d1d2f-101">The inputs for the Azure Machine Learning web service endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMachineLearningWebServiceInputs ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d1d2f-102">AzureMachineLearningWebServiceInputs クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d1d2f-102">Initializes a new instance of the AzureMachineLearningWebServiceInputs class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMachineLearningWebServiceInputs (string name = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn&gt; columnNames = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn&gt; columnNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional columnNames As IList(Of AzureMachineLearningWebServiceInputColumn) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs (name, columnNames)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="columnNames" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d1d2f-103">入力の名前。</span><span class="sxs-lookup"><span data-stu-id="d1d2f-103">The name of the input.</span></span> <span data-ttu-id="d1d2f-104">これは、エンドポイントの作成中に指定された名前です。</span><span class="sxs-lookup"><span data-stu-id="d1d2f-104">This is the name provided while authoring the endpoint.</span></span></param>
        <param name="columnNames"><span data-ttu-id="d1d2f-105">Azure Machine Learning web サービス エンドポイントの入力列の一覧。</span><span class="sxs-lookup"><span data-stu-id="d1d2f-105">A list of input columns for the Azure Machine Learning web service endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="d1d2f-106">AzureMachineLearningWebServiceInputs クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d1d2f-106">Initializes a new instance of the AzureMachineLearningWebServiceInputs class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ColumnNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn&gt; ColumnNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn&gt; ColumnNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs.ColumnNames" />
      <MemberSignature Language="VB.NET" Value="Public Property ColumnNames As IList(Of AzureMachineLearningWebServiceInputColumn)" />
      <MemberSignature Language="F#" Value="member this.ColumnNames : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs.ColumnNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="columnNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1d2f-107">取得または Azure Machine Learning web サービス エンドポイントの入力列の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="d1d2f-107">Gets or sets a list of input columns for the Azure Machine Learning web service endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1d2f-108">取得または入力の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="d1d2f-108">Gets or sets the name of the input.</span></span> <span data-ttu-id="d1d2f-109">これは、エンドポイントの作成中に指定された名前です。</span><span class="sxs-lookup"><span data-stu-id="d1d2f-109">This is the name provided while authoring the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
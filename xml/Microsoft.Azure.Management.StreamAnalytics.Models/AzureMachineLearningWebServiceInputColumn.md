<Type Name="AzureMachineLearningWebServiceInputColumn" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn">
  <TypeSignature Language="C#" Value="public class AzureMachineLearningWebServiceInputColumn" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMachineLearningWebServiceInputColumn extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMachineLearningWebServiceInputColumn" />
  <TypeSignature Language="F#" Value="type AzureMachineLearningWebServiceInputColumn = class" />
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
            <span data-ttu-id="bc698-101">Azure Machine Learning web サービス エンドポイントの入力列を説明します。</span><span class="sxs-lookup"><span data-stu-id="bc698-101">Describes an input column for the Azure Machine Learning web service endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMachineLearningWebServiceInputColumn ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bc698-102">AzureMachineLearningWebServiceInputColumn クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bc698-102">Initializes a new instance of the AzureMachineLearningWebServiceInputColumn class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMachineLearningWebServiceInputColumn (string name = null, string dataType = null, Nullable&lt;int&gt; mapTo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string dataType, valuetype System.Nullable`1&lt;int32&gt; mapTo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn.#ctor(System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional dataType As String = null, Optional mapTo As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn : string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn (name, dataType, mapTo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="dataType" Type="System.String" />
        <Parameter Name="mapTo" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="bc698-103">入力列の名前。</span><span class="sxs-lookup"><span data-stu-id="bc698-103">The name of the input column.</span></span></param>
        <param name="dataType"><span data-ttu-id="bc698-104">(Azure Machine Learning がサポートされている) データは、入力列の型します。</span><span class="sxs-lookup"><span data-stu-id="bc698-104">The (Azure Machine Learning supported) data type of the input column.</span></span> <span data-ttu-id="bc698-105">有効な Azure Machine Learning データ型の一覧については、https://msdn.microsoft.com/en-us/library/azure/dn905923.aspx で説明します。</span><span class="sxs-lookup"><span data-stu-id="bc698-105">A list of valid  Azure Machine Learning data types are described at https://msdn.microsoft.com/en-us/library/azure/dn905923.aspx .</span></span></param>
        <param name="mapTo"><span data-ttu-id="bc698-106">0 から始まるインデックス関数パラメーターのこの入力にマップします。</span><span class="sxs-lookup"><span data-stu-id="bc698-106">The zero based index of the function parameter this input maps to.</span></span></param>
        <summary>
            <span data-ttu-id="bc698-107">AzureMachineLearningWebServiceInputColumn クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bc698-107">Initializes a new instance of the AzureMachineLearningWebServiceInputColumn class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataType">
      <MemberSignature Language="C#" Value="public string DataType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn.DataType" />
      <MemberSignature Language="VB.NET" Value="Public Property DataType As String" />
      <MemberSignature Language="F#" Value="member this.DataType : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn.DataType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bc698-108">取得または入力列の (Azure Machine Learning がサポートされている) データ型を設定します。</span><span class="sxs-lookup"><span data-stu-id="bc698-108">Gets or sets the (Azure Machine Learning supported) data type of the input column.</span></span> <span data-ttu-id="bc698-109">有効な Azure Machine Learning データ型の一覧については、https://msdn.microsoft.com/en-us/library/azure/dn905923.aspx で説明します。</span><span class="sxs-lookup"><span data-stu-id="bc698-109">A list of valid  Azure Machine Learning data types are described at https://msdn.microsoft.com/en-us/library/azure/dn905923.aspx .</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MapTo">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MapTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MapTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn.MapTo" />
      <MemberSignature Language="VB.NET" Value="Public Property MapTo As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MapTo : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn.MapTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mapTo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bc698-110">取得または設定の 0 から始まる入力された関数パラメーターのインデックスにマップします。</span><span class="sxs-lookup"><span data-stu-id="bc698-110">Gets or sets the zero based index of the function parameter this input maps to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputColumn.Name" />
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
            <span data-ttu-id="bc698-111">取得または入力列の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="bc698-111">Gets or sets the name of the input column.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
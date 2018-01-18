<Type Name="FunctionInput" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput">
  <TypeSignature Language="C#" Value="public class FunctionInput" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FunctionInput extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput" />
  <TypeSignature Language="VB.NET" Value="Public Class FunctionInput" />
  <TypeSignature Language="F#" Value="type FunctionInput = class" />
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
            <span data-ttu-id="38755-101">関数の 1 つの入力パラメーターをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="38755-101">Describes one input parameter of a function.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FunctionInput ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="38755-102">FunctionInput クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="38755-102">Initializes a new instance of the FunctionInput class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FunctionInput (string dataType = null, Nullable&lt;bool&gt; isConfigurationParameter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string dataType, valuetype System.Nullable`1&lt;bool&gt; isConfigurationParameter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput.#ctor(System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional dataType As String = null, Optional isConfigurationParameter As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput : string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput (dataType, isConfigurationParameter)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dataType" Type="System.String" />
        <Parameter Name="isConfigurationParameter" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="dataType"><span data-ttu-id="38755-103">(Azure Stream Analytics がサポートされている) データは、関数の入力パラメーターの型します。</span><span class="sxs-lookup"><span data-stu-id="38755-103">The (Azure Stream Analytics supported) data type of the function input parameter.</span></span> <span data-ttu-id="38755-104">有効な Azure Stream Analytics データ型の一覧が https://msdn.microsoft.com/en-us/library/azure/dn835065.aspx で説明されています。</span><span class="sxs-lookup"><span data-stu-id="38755-104">A list of valid Azure Stream Analytics data types are described at https://msdn.microsoft.com/en-us/library/azure/dn835065.aspx</span></span></param>
        <param name="isConfigurationParameter"><span data-ttu-id="38755-105">構成パラメーターは、パラメーターを示すフラグ。</span><span class="sxs-lookup"><span data-stu-id="38755-105">A flag indicating if the parameter is a configuration parameter.</span></span> <span data-ttu-id="38755-106">True この入力パラメーターが予想される場合、定数であります。</span><span class="sxs-lookup"><span data-stu-id="38755-106">True if this input parameter is expected to be a constant.</span></span> <span data-ttu-id="38755-107">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="38755-107">Default is false.</span></span></param>
        <summary>
            <span data-ttu-id="38755-108">FunctionInput クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="38755-108">Initializes a new instance of the FunctionInput class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataType">
      <MemberSignature Language="C#" Value="public string DataType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput.DataType" />
      <MemberSignature Language="VB.NET" Value="Public Property DataType As String" />
      <MemberSignature Language="F#" Value="member this.DataType : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput.DataType" />
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
            <span data-ttu-id="38755-109">取得または関数の入力パラメーターの (Azure Stream Analytics がサポートされている) データ型を設定します。</span><span class="sxs-lookup"><span data-stu-id="38755-109">Gets or sets the (Azure Stream Analytics supported) data type of the function input parameter.</span></span> <span data-ttu-id="38755-110">有効な Azure Stream Analytics データ型の一覧が https://msdn.microsoft.com/en-us/library/azure/dn835065.aspx で説明されています。</span><span class="sxs-lookup"><span data-stu-id="38755-110">A list of valid Azure Stream Analytics data types are described at https://msdn.microsoft.com/en-us/library/azure/dn835065.aspx</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsConfigurationParameter">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsConfigurationParameter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsConfigurationParameter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput.IsConfigurationParameter" />
      <MemberSignature Language="VB.NET" Value="Public Property IsConfigurationParameter As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsConfigurationParameter : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput.IsConfigurationParameter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isConfigurationParameter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38755-111">取得または設定のパラメーターは、パラメーターを示すフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="38755-111">Gets or sets a flag indicating if the parameter is a configuration parameter.</span></span> <span data-ttu-id="38755-112">True この入力パラメーターが予想される場合、定数であります。</span><span class="sxs-lookup"><span data-stu-id="38755-112">True if this input parameter is expected to be a constant.</span></span> <span data-ttu-id="38755-113">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="38755-113">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
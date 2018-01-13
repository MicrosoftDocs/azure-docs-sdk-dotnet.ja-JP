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
            Azure Machine Learning web サービス エンドポイントの入力列を説明します。
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
            AzureMachineLearningWebServiceInputColumn クラスの新しいインスタンスを初期化します。
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
        <param name="name">入力列の名前。</param>
        <param name="dataType">(Azure Machine Learning がサポートされている) データは、入力列の型します。 有効な Azure Machine Learning データ型の一覧については、https://msdn.microsoft.com/en-us/library/azure/dn905923.aspx で説明します。</param>
        <param name="mapTo">0 から始まるインデックス関数パラメーターのこの入力にマップします。</param>
        <summary>
            AzureMachineLearningWebServiceInputColumn クラスの新しいインスタンスを初期化します。
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
            取得または入力列の (Azure Machine Learning がサポートされている) データ型を設定します。 有効な Azure Machine Learning データ型の一覧については、https://msdn.microsoft.com/en-us/library/azure/dn905923.aspx で説明します。
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
            取得または設定の 0 から始まる入力された関数パラメーターのインデックスにマップします。
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
            取得または入力列の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
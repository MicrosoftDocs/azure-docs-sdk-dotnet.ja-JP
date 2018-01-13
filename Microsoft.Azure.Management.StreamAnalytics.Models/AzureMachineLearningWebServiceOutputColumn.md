<Type Name="AzureMachineLearningWebServiceOutputColumn" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn">
  <TypeSignature Language="C#" Value="public class AzureMachineLearningWebServiceOutputColumn" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMachineLearningWebServiceOutputColumn extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMachineLearningWebServiceOutputColumn" />
  <TypeSignature Language="F#" Value="type AzureMachineLearningWebServiceOutputColumn = class" />
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
            Azure Machine Learning web サービス エンドポイントの出力列を説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMachineLearningWebServiceOutputColumn ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AzureMachineLearningWebServiceOutputColumn クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMachineLearningWebServiceOutputColumn (string name = null, string dataType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string dataType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional dataType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn : string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn (name, dataType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="dataType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">出力列の名前です。</param>
        <param name="dataType">(Azure Machine Learning がサポートされている) データは、出力列の型します。 有効な Azure Machine Learning データ型の一覧については、https://msdn.microsoft.com/en-us/library/azure/dn905923.aspx で説明します。</param>
        <summary>
            AzureMachineLearningWebServiceOutputColumn クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataType">
      <MemberSignature Language="C#" Value="public string DataType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn.DataType" />
      <MemberSignature Language="VB.NET" Value="Public Property DataType As String" />
      <MemberSignature Language="F#" Value="member this.DataType : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn.DataType" />
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
            取得または出力列の (Azure Machine Learning がサポートされている) データ型を設定します。 有効な Azure Machine Learning データ型の一覧については、https://msdn.microsoft.com/en-us/library/azure/dn905923.aspx で説明します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn.Name" />
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
            取得または出力列の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
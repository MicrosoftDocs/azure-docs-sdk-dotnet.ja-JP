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
            関数の 1 つの入力パラメーターをについて説明します。
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
            FunctionInput クラスの新しいインスタンスを初期化します。
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
        <param name="dataType">(Azure Stream Analytics がサポートされている) データは、関数の入力パラメーターの型します。 有効な Azure Stream Analytics データ型の一覧が https://msdn.microsoft.com/en-us/library/azure/dn835065.aspx で説明されています。</param>
        <param name="isConfigurationParameter">構成パラメーターは、パラメーターを示すフラグ。 True この入力パラメーターが予想される場合、定数であります。 既定値は false です。</param>
        <summary>
            FunctionInput クラスの新しいインスタンスを初期化します。
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
            取得または関数の入力パラメーターの (Azure Stream Analytics がサポートされている) データ型を設定します。 有効な Azure Stream Analytics データ型の一覧が https://msdn.microsoft.com/en-us/library/azure/dn835065.aspx で説明されています。
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
            取得または設定のパラメーターは、パラメーターを示すフラグを設定します。 True この入力パラメーターが予想される場合、定数であります。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
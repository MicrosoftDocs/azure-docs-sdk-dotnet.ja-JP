<Type Name="FunctionOutput" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionOutput">
  <TypeSignature Language="C#" Value="public class FunctionOutput" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FunctionOutput extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.FunctionOutput" />
  <TypeSignature Language="VB.NET" Value="Public Class FunctionOutput" />
  <TypeSignature Language="F#" Value="type FunctionOutput = class" />
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
            関数の出力をについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FunctionOutput ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.FunctionOutput.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            FunctionOutput クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FunctionOutput (string dataType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string dataType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.FunctionOutput.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional dataType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.FunctionOutput : string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.FunctionOutput" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.FunctionOutput dataType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dataType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="dataType">関数の出力の (Azure Stream Analytics がサポートされている) データ型。 有効な Azure Stream Analytics データ型の一覧が https://msdn.microsoft.com/en-us/library/azure/dn835065.aspx で説明されています。</param>
        <summary>
            FunctionOutput クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataType">
      <MemberSignature Language="C#" Value="public string DataType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.FunctionOutput.DataType" />
      <MemberSignature Language="VB.NET" Value="Public Property DataType As String" />
      <MemberSignature Language="F#" Value="member this.DataType : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionOutput.DataType" />
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
            取得または、(Azure Stream Analytics がサポートされている) のデータ型、関数の出力を設定します。 有効な Azure Stream Analytics データ型の一覧が https://msdn.microsoft.com/en-us/library/azure/dn835065.aspx で説明されています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
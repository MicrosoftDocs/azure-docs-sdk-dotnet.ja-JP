<Type Name="Function" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.Function">
  <TypeSignature Language="C#" Value="public class Function : Microsoft.Azure.Management.StreamAnalytics.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Function extends Microsoft.Azure.Management.StreamAnalytics.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
  <TypeSignature Language="VB.NET" Value="Public Class Function&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type Function = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            名前付きの関数に関連付けられているすべての情報を含む関数オブジェクト。 ストリーミング ジョブの下では、すべての関数が含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Function ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Function.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            関数クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Function (string id = null, string name = null, string type = null, Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Function.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional properties As FunctionProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.Function : string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Function" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.Function (id, name, type, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties" />
      </Parameters>
      <Docs>
        <param name="id">リソース Id</param>
        <param name="name">リソース名</param>
        <param name="type">リソースの種類</param>
        <param name="properties">関数に関連付けられているプロパティです。</param>
        <summary>
            関数クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Function.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As FunctionProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Function.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または関数に関連付けられているプロパティを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
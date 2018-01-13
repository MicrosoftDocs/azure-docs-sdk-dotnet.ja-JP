<Type Name="DataLakeStoreAccountInfo" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo">
  <TypeSignature Language="C#" Value="public class DataLakeStoreAccountInfo : Microsoft.Azure.Management.DataLake.Analytics.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeStoreAccountInfo extends Microsoft.Azure.Management.DataLake.Analytics.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeStoreAccountInfo&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type DataLakeStoreAccountInfo = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Data Lake Store アカウントの情報です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeStoreAccountInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DataLakeStoreAccountInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeStoreAccountInfo (string name, string id = null, string type = null, string suffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string id, string type, string suffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional id As String = null, Optional type As String = null, Optional suffix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo : string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo (name, id, type, suffix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="suffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">リソース名</param>
        <param name="id">リソース Id</param>
        <param name="type">リソースの種類</param>
        <param name="suffix">Data Lake Store アカウントの省略可能なサフィックス。</param>
        <summary>
            DataLakeStoreAccountInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Suffix">
      <MemberSignature Language="C#" Value="public string Suffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Suffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo.Suffix" />
      <MemberSignature Language="VB.NET" Value="Public Property Suffix As String" />
      <MemberSignature Language="F#" Value="member this.Suffix : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo.Suffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.suffix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Data Lake Store アカウントの省略可能なサフィックスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="dataLakeStoreAccountInfo.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
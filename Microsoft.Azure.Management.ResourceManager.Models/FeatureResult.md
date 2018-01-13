<Type Name="FeatureResult" FullName="Microsoft.Azure.Management.ResourceManager.Models.FeatureResult">
  <TypeSignature Language="C#" Value="public class FeatureResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FeatureResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.FeatureResult" />
  <TypeSignature Language="VB.NET" Value="Public Class FeatureResult" />
  <TypeSignature Language="F#" Value="type FeatureResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            機能の情報をプレビューします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FeatureResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.FeatureResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            FeatureResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FeatureResult (string name = null, Microsoft.Azure.Management.ResourceManager.Models.FeatureProperties properties = null, string id = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.ResourceManager.Models.FeatureProperties properties, string id, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.FeatureResult.#ctor(System.String,Microsoft.Azure.Management.ResourceManager.Models.FeatureProperties,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional properties As FeatureProperties = null, Optional id As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.FeatureResult : string * Microsoft.Azure.Management.ResourceManager.Models.FeatureProperties * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.FeatureResult" Usage="new Microsoft.Azure.Management.ResourceManager.Models.FeatureResult (name, properties, id, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.ResourceManager.Models.FeatureProperties" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">機能の名前。</param>
        <param name="properties">プレビュー機能のプロパティです。</param>
        <param name="id">フィーチャーのリソース ID です。</param>
        <param name="type">フィーチャーのリソースの種類。</param>
        <summary>
            FeatureResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.FeatureResult.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.FeatureResult.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフィーチャーのリソース ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.FeatureResult.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.FeatureResult.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            取得または機能の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.FeatureProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.FeatureProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.FeatureResult.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As FeatureProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.ResourceManager.Models.FeatureProperties with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.FeatureResult.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.FeatureProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはのプレビュー機能のプロパティを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.FeatureResult.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.FeatureResult.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフィーチャーのリソースの種類を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
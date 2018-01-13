<Type Name="VnetValidationTestFailure" FullName="Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure">
  <TypeSignature Language="C#" Value="public class VnetValidationTestFailure : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VnetValidationTestFailure extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure" />
  <TypeSignature Language="VB.NET" Value="Public Class VnetValidationTestFailure&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type VnetValidationTestFailure = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            NSG と UDR の検証中に失敗したテストを記述するクラス。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetValidationTestFailure ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            VnetValidationTestFailure クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetValidationTestFailure (string id = null, string name = null, string kind = null, string type = null, string testName = null, string details = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string testName, string details) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional testName As String = null, Optional details As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure : string * string * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure" Usage="new Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure (id, name, kind, type, testName, details)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="testName" Type="System.String" />
        <Parameter Name="details" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前です。</param>
        <param name="kind">リソースの種類。</param>
        <param name="type">リソースの種類。</param>
        <param name="testName">失敗したテストの名前。</param>
        <param name="details">詳細、失敗の原因など、ブロックしているルールの名前など。</param>
        <summary>
            VnetValidationTestFailure クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public string Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As String" />
      <MemberSignature Language="F#" Value="member this.Details : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはなど、ブロックしているルールの名前など、エラーの原因の詳細を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestName">
      <MemberSignature Language="C#" Value="public string TestName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TestName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure.TestName" />
      <MemberSignature Language="VB.NET" Value="Public Property TestName As String" />
      <MemberSignature Language="F#" Value="member this.TestName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VnetValidationTestFailure.TestName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.testName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または失敗したテストの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
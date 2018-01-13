<Type Name="DomainControlCenterSsoRequest" FullName="Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest">
  <TypeSignature Language="C#" Value="public class DomainControlCenterSsoRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DomainControlCenterSsoRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class DomainControlCenterSsoRequest" />
  <TypeSignature Language="F#" Value="type DomainControlCenterSsoRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ドメイン管理のシングル サインオン要求情報です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DomainControlCenterSsoRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DomainControlCenterSsoRequest クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DomainControlCenterSsoRequest (string url = null, string postParameterKey = null, string postParameterValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string url, string postParameterKey, string postParameterValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional url As String = null, Optional postParameterKey As String = null, Optional postParameterValue As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest : string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest" Usage="new Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest (url, postParameterKey, postParameterValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="postParameterKey" Type="System.String" />
        <Parameter Name="postParameterValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="url">シングル サインオン要求のなる URL です。</param>
        <param name="postParameterKey">Post パラメーターのキー。</param>
        <param name="postParameterValue">パラメーターの値をポストします。 クライアントは、' アプリケーション/x-www-form-urlencoded' エンコードにこの値を使用してください。</param>
        <summary>
            DomainControlCenterSsoRequest クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostParameterKey">
      <MemberSignature Language="C#" Value="public string PostParameterKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PostParameterKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest.PostParameterKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PostParameterKey As String" />
      <MemberSignature Language="F#" Value="member this.PostParameterKey : string" Usage="Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest.PostParameterKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="postParameterKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得では、パラメーターのキーを投稿します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostParameterValue">
      <MemberSignature Language="C#" Value="public string PostParameterValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PostParameterValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest.PostParameterValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PostParameterValue As String" />
      <MemberSignature Language="F#" Value="member this.PostParameterValue : string" Usage="Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest.PostParameterValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="postParameterValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得では、パラメーターの値をポストします。 クライアントは、' アプリケーション/x-www-form-urlencoded' エンコードにこの値を使用してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            シングル サインオン要求のなる URL を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
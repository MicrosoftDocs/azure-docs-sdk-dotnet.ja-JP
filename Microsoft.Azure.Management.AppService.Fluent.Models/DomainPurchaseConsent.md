<Type Name="DomainPurchaseConsent" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent">
  <TypeSignature Language="C#" Value="public class DomainPurchaseConsent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DomainPurchaseConsent extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent" />
  <TypeSignature Language="VB.NET" Value="Public Class DomainPurchaseConsent" />
  <TypeSignature Language="F#" Value="type DomainPurchaseConsent = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ドメイン購買同意を表すオブジェクト法的契約書に同意します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DomainPurchaseConsent ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DomainPurchaseConsent クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DomainPurchaseConsent (System.Collections.Generic.IList&lt;string&gt; agreementKeys = null, string agreedBy = null, Nullable&lt;DateTime&gt; agreedAt = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; agreementKeys, string agreedBy, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; agreedAt) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent.#ctor(System.Collections.Generic.IList{System.String},System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional agreementKeys As IList(Of String) = null, Optional agreedBy As String = null, Optional agreedAt As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent : System.Collections.Generic.IList&lt;string&gt; * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent (agreementKeys, agreedBy, agreedAt)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="agreementKeys" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="agreedBy" Type="System.String" />
        <Parameter Name="agreedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="agreementKeys">該当する法的な契約キーの一覧です。 この一覧は、下にある ListLegalAgreements API を使用して取得できる&lt;コード&gt;TopLevelDomain&lt;/code&gt;リソース。</param>
        <param name="agreedBy">クライアント IP アドレス。</param>
        <param name="agreedAt">契約書が許可されたときのタイムスタンプ。</param>
        <summary>
            DomainPurchaseConsent クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AgreedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AgreedAt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AgreedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent.AgreedAt" />
      <MemberSignature Language="VB.NET" Value="Public Property AgreedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AgreedAt : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent.AgreedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="agreedAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または契約が受け入れられたときに、タイムスタンプを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AgreedBy">
      <MemberSignature Language="C#" Value="public string AgreedBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AgreedBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent.AgreedBy" />
      <MemberSignature Language="VB.NET" Value="Public Property AgreedBy As String" />
      <MemberSignature Language="F#" Value="member this.AgreedBy : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent.AgreedBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="agreedBy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクライアントの IP アドレスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AgreementKeys">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AgreementKeys { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AgreementKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent.AgreementKeys" />
      <MemberSignature Language="VB.NET" Value="Public Property AgreementKeys As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AgreementKeys : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent.AgreementKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="agreementKeys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または該当する法的な契約キーの一覧を設定します。 この一覧は、下にある ListLegalAgreements API を使用して取得できる&amp;lt; コード&amp;gt;TopLevelDomain&amp;lt;/code&amp;gt; リソース。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
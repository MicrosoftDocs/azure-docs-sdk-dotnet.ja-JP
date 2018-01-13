<Type Name="AvailableProvidersList" FullName="Microsoft.Azure.Management.Network.Models.AvailableProvidersList">
  <TypeSignature Language="C#" Value="public class AvailableProvidersList" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AvailableProvidersList extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.AvailableProvidersList" />
  <TypeSignature Language="VB.NET" Value="Public Class AvailableProvidersList" />
  <TypeSignature Language="F#" Value="type AvailableProvidersList = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            詳細と使用可能な国の一覧です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailableProvidersList ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AvailableProvidersList.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AvailableProvidersList クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailableProvidersList (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry&gt; countries);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry&gt; countries) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AvailableProvidersList.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (countries As IList(Of AvailableProvidersListCountry))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.AvailableProvidersList : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry&gt; -&gt; Microsoft.Azure.Management.Network.Models.AvailableProvidersList" Usage="new Microsoft.Azure.Management.Network.Models.AvailableProvidersList countries" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="countries" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry&gt;" />
      </Parameters>
      <Docs>
        <param name="countries">利用可能な国の一覧です。</param>
        <summary>
            AvailableProvidersList クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Countries">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry&gt; Countries { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry&gt; Countries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AvailableProvidersList.Countries" />
      <MemberSignature Language="VB.NET" Value="Public Property Countries As IList(Of AvailableProvidersListCountry)" />
      <MemberSignature Language="F#" Value="member this.Countries : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.AvailableProvidersList.Countries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="countries")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersListCountry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または使用可能な国の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AvailableProvidersList.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="availableProvidersList.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
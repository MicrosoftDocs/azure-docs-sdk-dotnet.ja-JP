<Type Name="ContainerServiceSshConfiguration" FullName="Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration">
  <TypeSignature Language="C#" Value="public class ContainerServiceSshConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerServiceSshConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerServiceSshConfiguration" />
  <TypeSignature Language="F#" Value="type ContainerServiceSshConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Azure で実行されている Linux ベースの Vm の SSH 構成します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceSshConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ContainerServiceSshConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceSshConfiguration (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ContainerServiceSshPublicKey&gt; publicKeys);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerServiceSshPublicKey&gt; publicKeys) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.ContainerServiceSshPublicKey})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (publicKeys As IList(Of ContainerServiceSshPublicKey))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ContainerServiceSshPublicKey&gt; -&gt; Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration" Usage="new Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration publicKeys" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="publicKeys" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ContainerServiceSshPublicKey&gt;" />
      </Parameters>
      <Docs>
        <param name="publicKeys">Linux ベースの Vm での認証に使用する SSH 公開キーの一覧。</param>
        <summary>
            ContainerServiceSshConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicKeys">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ContainerServiceSshPublicKey&gt; PublicKeys { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerServiceSshPublicKey&gt; PublicKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration.PublicKeys" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicKeys As IList(Of ContainerServiceSshPublicKey)" />
      <MemberSignature Language="F#" Value="member this.PublicKeys : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ContainerServiceSshPublicKey&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration.PublicKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="publicKeys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ContainerServiceSshPublicKey&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Linux ベースの Vm での認証に使用する SSH 公開キーの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="containerServiceSshConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
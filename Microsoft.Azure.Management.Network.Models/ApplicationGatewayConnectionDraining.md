<Type Name="ApplicationGatewayConnectionDraining" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayConnectionDraining" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayConnectionDraining extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayConnectionDraining" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayConnectionDraining = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            バックエンド サーバーが、構成から削除された後に、指定した時間のアクティブ化するバックエンド サーバーに対して開いている接続は、接続のドレインできます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayConnectionDraining ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ApplicationGatewayConnectionDraining クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayConnectionDraining (bool enabled, int drainTimeoutInSec);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool enabled, int32 drainTimeoutInSec) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining.#ctor(System.Boolean,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (enabled As Boolean, drainTimeoutInSec As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining : bool * int -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining (enabled, drainTimeoutInSec)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
        <Parameter Name="drainTimeoutInSec" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="enabled">接続のドレインが有効かどうか。</param>
        <param name="drainTimeoutInSec">接続のドレインを秒単位の数はアクティブです。 使用可能な値は、1 秒 ~ 3600 秒です。</param>
        <summary>
            ApplicationGatewayConnectionDraining クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DrainTimeoutInSec">
      <MemberSignature Language="C#" Value="public int DrainTimeoutInSec { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DrainTimeoutInSec" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining.DrainTimeoutInSec" />
      <MemberSignature Language="VB.NET" Value="Public Property DrainTimeoutInSec As Integer" />
      <MemberSignature Language="F#" Value="member this.DrainTimeoutInSec : int with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining.DrainTimeoutInSec" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="drainTimeoutInSec")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアクティブな接続のドレインが秒数を設定します。
            使用可能な値は、1 秒 ~ 3600 秒です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public bool Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.Enabled : bool with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または接続のドレインが有効かどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayConnectionDraining.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="applicationGatewayConnectionDraining.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
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
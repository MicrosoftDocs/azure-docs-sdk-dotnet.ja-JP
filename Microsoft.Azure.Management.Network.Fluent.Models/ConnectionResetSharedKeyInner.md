<Type Name="ConnectionResetSharedKeyInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner">
  <TypeSignature Language="C#" Value="public class ConnectionResetSharedKeyInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnectionResetSharedKeyInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnectionResetSharedKeyInner" />
  <TypeSignature Language="F#" Value="type ConnectionResetSharedKeyInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectionResetSharedKeyInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ConnectionResetSharedKeyInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectionResetSharedKeyInner (int keyLength);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 keyLength) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner.#ctor(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyLength As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner : int -&gt; Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner keyLength" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyLength" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="keyLength">共有キーの長さをリセットする仮想ネットワーク接続は、1 と 128 の間で必要があります。</param>
        <summary>
            ConnectionResetSharedKeyInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyLength">
      <MemberSignature Language="C#" Value="public int KeyLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 KeyLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner.KeyLength" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyLength As Integer" />
      <MemberSignature Language="F#" Value="member this.KeyLength : int with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner.KeyLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyLength")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想ネットワーク接続のリセットの共有キーの長さを設定、1 と 128 の間で必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="connectionResetSharedKeyInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
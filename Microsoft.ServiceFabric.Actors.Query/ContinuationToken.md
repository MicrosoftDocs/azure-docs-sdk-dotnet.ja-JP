<Type Name="ContinuationToken" FullName="Microsoft.ServiceFabric.Actors.Query.ContinuationToken">
  <TypeSignature Language="C#" Value="public class ContinuationToken" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContinuationToken extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Query.ContinuationToken" />
  <TypeSignature Language="VB.NET" Value="Public Class ContinuationToken" />
  <TypeSignature Language="F#" Value="type ContinuationToken = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="ContinuationToken", Namespace="urn:actors")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            クエリ操作の継続トークンを表します。
            </summary>
    <remarks>メソッドを使用して結果のセットの一部を返す可能性があります、<see cref="T:Microsoft.ServiceFabric.Actors.Query.PagedResult`1" />オブジェクトが使用可能な結果の次のセットを返す、後続の呼び出しで使用できるオブジェクトにも継続トークンを返します。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContinuationToken (object marker);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object marker) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Query.ContinuationToken.#ctor(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (marker As Object)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Query.ContinuationToken : obj -&gt; Microsoft.ServiceFabric.Actors.Query.ContinuationToken" Usage="new Microsoft.ServiceFabric.Actors.Query.ContinuationToken marker" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="marker" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="marker">次の使用可能な結果セットの取得に使用されるマーカー。</param>
        <summary>
            <see cref="T:Microsoft.ServiceFabric.Actors.Query.ContinuationToken" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Marker">
      <MemberSignature Language="C#" Value="public object Marker { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Marker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Query.ContinuationToken.Marker" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Marker As Object" />
      <MemberSignature Language="F#" Value="member this.Marker : obj" Usage="Microsoft.ServiceFabric.Actors.Query.ContinuationToken.Marker" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="Marker", Order=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            次の使用可能な結果セットのフェッチに使用するマーカーを取得します。
            </summary>
        <value>次の使用可能な結果セットをフェッチするために使用するマーカー。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
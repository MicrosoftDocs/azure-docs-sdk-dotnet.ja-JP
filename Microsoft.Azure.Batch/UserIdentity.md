<Type Name="UserIdentity" FullName="Microsoft.Azure.Batch.UserIdentity">
  <TypeSignature Language="C#" Value="public class UserIdentity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserIdentity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.UserIdentity" />
  <TypeSignature Language="VB.NET" Value="Public Class UserIdentity" />
  <TypeSignature Language="F#" Value="type UserIdentity = class&#xA;    interface ITransportObjectProvider&lt;UserIdentity&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            タスクが実行されるユーザー id の定義。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserIdentity (Microsoft.Azure.Batch.AutoUserSpecification autoUserSpecification);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.AutoUserSpecification autoUserSpecification) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.UserIdentity.#ctor(Microsoft.Azure.Batch.AutoUserSpecification)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.UserIdentity : Microsoft.Azure.Batch.AutoUserSpecification -&gt; Microsoft.Azure.Batch.UserIdentity" Usage="new Microsoft.Azure.Batch.UserIdentity autoUserSpecification" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="autoUserSpecification" Type="Microsoft.Azure.Batch.AutoUserSpecification" />
      </Parameters>
      <Docs>
        <param name="autoUserSpecification">タスクが実行される自動ユーザー。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.UserIdentity" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserIdentity (string userName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string userName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.UserIdentity.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (userName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.UserIdentity : string -&gt; Microsoft.Azure.Batch.UserIdentity" Usage="new Microsoft.Azure.Batch.UserIdentity userName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="userName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="userName">ユーザー id のユーザー名。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.UserIdentity" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoUser">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.AutoUserSpecification AutoUser { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.AutoUserSpecification AutoUser" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.UserIdentity.AutoUser" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoUser As AutoUserSpecification" />
      <MemberSignature Language="F#" Value="member this.AutoUser : Microsoft.Azure.Batch.AutoUserSpecification" Usage="Microsoft.Azure.Batch.UserIdentity.AutoUser" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AutoUserSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タスクが実行される自動ユーザーを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            <see cref="P:Microsoft.Azure.Batch.UserIdentity.UserName" />と<see cref="P:Microsoft.Azure.Batch.UserIdentity.AutoUser" />プロパティは相互に排他的です。 いずれかを指定する必要がありますが、両方は使用できません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public string UserName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.UserIdentity.UserName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserName As String" />
      <MemberSignature Language="F#" Value="member this.UserName : string" Usage="Microsoft.Azure.Batch.UserIdentity.UserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タスクが実行されるユーザー id の名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            <see cref="P:Microsoft.Azure.Batch.UserIdentity.UserName" />と<see cref="P:Microsoft.Azure.Batch.UserIdentity.AutoUser" />プロパティは相互に排他的です。 いずれかを指定する必要がありますが、両方は使用できません。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>
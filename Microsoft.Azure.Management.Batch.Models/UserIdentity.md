<Type Name="UserIdentity" FullName="Microsoft.Azure.Management.Batch.Models.UserIdentity">
  <TypeSignature Language="C#" Value="public class UserIdentity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserIdentity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.UserIdentity" />
  <TypeSignature Language="VB.NET" Value="Public Class UserIdentity" />
  <TypeSignature Language="F#" Value="type UserIdentity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            タスクが実行されるユーザー id の定義。
            </summary>
    <remarks>
            ユーザー名と autoUser プロパティの両方ではなくはどちらかを指定します。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserIdentity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.UserIdentity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            UserIdentity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserIdentity (string userName = null, Microsoft.Azure.Management.Batch.Models.AutoUserSpecification autoUser = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string userName, class Microsoft.Azure.Management.Batch.Models.AutoUserSpecification autoUser) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.UserIdentity.#ctor(System.String,Microsoft.Azure.Management.Batch.Models.AutoUserSpecification)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional userName As String = null, Optional autoUser As AutoUserSpecification = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.UserIdentity : string * Microsoft.Azure.Management.Batch.Models.AutoUserSpecification -&gt; Microsoft.Azure.Management.Batch.Models.UserIdentity" Usage="new Microsoft.Azure.Management.Batch.Models.UserIdentity (userName, autoUser)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="autoUser" Type="Microsoft.Azure.Management.Batch.Models.AutoUserSpecification" />
      </Parameters>
      <Docs>
        <param name="userName">タスクが実行されるユーザー id の名前。</param>
        <param name="autoUser">タスクが実行される自動ユーザー。</param>
        <summary>
            UserIdentity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoUser">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.AutoUserSpecification AutoUser { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.AutoUserSpecification AutoUser" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.UserIdentity.AutoUser" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoUser As AutoUserSpecification" />
      <MemberSignature Language="F#" Value="member this.AutoUser : Microsoft.Azure.Management.Batch.Models.AutoUserSpecification with get, set" Usage="Microsoft.Azure.Management.Batch.Models.UserIdentity.AutoUser" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoUser")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.AutoUserSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクが実行される自動ユーザーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            ユーザー名と autoUser プロパティが相互に排他的です。いずれかを指定する必要がありますが、両方は使用できません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public string UserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.UserIdentity.UserName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserName As String" />
      <MemberSignature Language="F#" Value="member this.UserName : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.UserIdentity.UserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクが実行されるユーザー id の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            ユーザー名と autoUser プロパティが相互に排他的です。いずれかを指定する必要がありますが、両方は使用できません。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>
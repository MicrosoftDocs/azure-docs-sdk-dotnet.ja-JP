<Type Name="UserAccount" FullName="Microsoft.Azure.Management.Batch.Models.UserAccount">
  <TypeSignature Language="C#" Value="public class UserAccount" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserAccount extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.UserAccount" />
  <TypeSignature Language="VB.NET" Value="Public Class UserAccount" />
  <TypeSignature Language="F#" Value="type UserAccount = class" />
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
            Azure Batch のノードにユーザーを作成するためのプロパティです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserAccount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.UserAccount.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            UserAccount クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserAccount (string name, string password, Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; elevationLevel = null, Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration linuxUserConfiguration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string password, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; elevationLevel, class Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration linuxUserConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.UserAccount.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.Batch.Models.ElevationLevel},Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.UserAccount : string * string * Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; * Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration -&gt; Microsoft.Azure.Management.Batch.Models.UserAccount" Usage="new Microsoft.Azure.Management.Batch.Models.UserAccount (name, password, elevationLevel, linuxUserConfiguration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="elevationLevel" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt;" />
        <Parameter Name="linuxUserConfiguration" Type="Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration" />
      </Parameters>
      <Docs>
        <param name="name">ユーザー アカウント名。</param>
        <param name="password">ユーザー アカウントのパスワードです。</param>
        <param name="elevationLevel">ユーザー アカウントの昇格レベル。</param>
        <param name="linuxUserConfiguration">ユーザー アカウントの Linux 固有のユーザーの構成。</param>
        <summary>
            UserAccount クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElevationLevel">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; ElevationLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; ElevationLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.UserAccount.ElevationLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ElevationLevel As Nullable(Of ElevationLevel)" />
      <MemberSignature Language="F#" Value="member this.ElevationLevel : Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.UserAccount.ElevationLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="elevationLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはユーザー アカウントの昇格のレベルを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            nonAdmin - 自動ユーザーは、管理者特権でのアクセス権のない標準ユーザーです。 管理 - 自動ユーザー昇格されたアクセス権を持つユーザーは、完全な管理者アクセス許可で操作を行います。 既定値は、nonAdmin です。 使用可能な値が含まれます: 'NonAdmin'、'Admin'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LinuxUserConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration LinuxUserConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration LinuxUserConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.UserAccount.LinuxUserConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property LinuxUserConfiguration As LinuxUserConfiguration" />
      <MemberSignature Language="F#" Value="member this.LinuxUserConfiguration : Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration with get, set" Usage="Microsoft.Azure.Management.Batch.Models.UserAccount.LinuxUserConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="linuxUserConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ユーザー アカウントの構成を Linux 固有のユーザー設定を取得またはします。
            </summary>
        <value>To be added.</value>
        <remarks>
            Windows のプールで指定した場合、このプロパティは無視されます。 指定しない場合、既定のオプションで、ユーザーが作成されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.UserAccount.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.UserAccount.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはユーザー アカウントの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.UserAccount.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.UserAccount.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはユーザー アカウントのパスワードを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.UserAccount.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="userAccount.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
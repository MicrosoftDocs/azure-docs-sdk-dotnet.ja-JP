<Type Name="UserAccount" FullName="Microsoft.Azure.Batch.UserAccount">
  <TypeSignature Language="C#" Value="public class UserAccount" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserAccount extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.UserAccount" />
  <TypeSignature Language="VB.NET" Value="Public Class UserAccount" />
  <TypeSignature Language="F#" Value="type UserAccount = class&#xA;    interface ITransportObjectProvider&lt;UserAccount&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Azure Batch ノード上に作成するユーザー アカウント。 ユーザー アカウントのセキュリティ コンテキストで実行するタスクを構成することがあります。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserAccount (string name, string password, Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt; elevationLevel = null, Microsoft.Azure.Batch.LinuxUserConfiguration linuxUserConfiguration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string password, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ElevationLevel&gt; elevationLevel, class Microsoft.Azure.Batch.LinuxUserConfiguration linuxUserConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.UserAccount.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ElevationLevel},Microsoft.Azure.Batch.LinuxUserConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.UserAccount : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt; * Microsoft.Azure.Batch.LinuxUserConfiguration -&gt; Microsoft.Azure.Batch.UserAccount" Usage="new Microsoft.Azure.Batch.UserAccount (name, password, elevationLevel, linuxUserConfiguration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="elevationLevel" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt;" />
        <Parameter Name="linuxUserConfiguration" Type="Microsoft.Azure.Batch.LinuxUserConfiguration" />
      </Parameters>
      <Docs>
        <param name="name">ユーザー アカウント名。</param>
        <param name="password">ユーザー アカウントのパスワードです。</param>
        <param name="elevationLevel">ユーザー アカウントの昇格レベル。</param>
        <param name="linuxUserConfiguration">追加のプロパティは、Linux ノード上のユーザー アカウントを作成するために使用します。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.UserAccount" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElevationLevel">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt; ElevationLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ElevationLevel&gt; ElevationLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.UserAccount.ElevationLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ElevationLevel As Nullable(Of ElevationLevel)" />
      <MemberSignature Language="F#" Value="member this.ElevationLevel : Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt; with get, set" Usage="Microsoft.Azure.Batch.UserAccount.ElevationLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはユーザー アカウントの昇格のレベルを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は、省略した場合、します。<see cref="F:Microsoft.Azure.Batch.Common.ElevationLevel.NonAdmin" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="LinuxUserConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.LinuxUserConfiguration LinuxUserConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.LinuxUserConfiguration LinuxUserConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.UserAccount.LinuxUserConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property LinuxUserConfiguration As LinuxUserConfiguration" />
      <MemberSignature Language="F#" Value="member this.LinuxUserConfiguration : Microsoft.Azure.Batch.LinuxUserConfiguration with get, set" Usage="Microsoft.Azure.Batch.UserAccount.LinuxUserConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.LinuxUserConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、Linux ノード上のユーザー アカウントを作成するために使用する追加のプロパティを設定します。
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.UserAccount.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Batch.UserAccount.Name" />
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
            取得またはユーザー アカウントの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.UserAccount.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Batch.UserAccount.Password" />
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
            取得またはユーザー アカウントのパスワードを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
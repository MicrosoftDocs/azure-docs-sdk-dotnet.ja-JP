<Type Name="AuthenticationTokenSettings" FullName="Microsoft.Azure.Batch.AuthenticationTokenSettings">
  <TypeSignature Language="C#" Value="public class AuthenticationTokenSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AuthenticationTokenSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.AuthenticationTokenSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class AuthenticationTokenSettings" />
  <TypeSignature Language="F#" Value="type AuthenticationTokenSettings = class&#xA;    interface ITransportObjectProvider&lt;AuthenticationTokenSettings&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            バッチを実行するタスクを使用する認証トークンの設定は、操作を処理します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationTokenSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.AuthenticationTokenSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.AuthenticationTokenSettings" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.AccessScope Access { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.AccessScope Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AuthenticationTokenSettings.Access" />
      <MemberSignature Language="VB.NET" Value="Public Property Access As AccessScope" />
      <MemberSignature Language="F#" Value="member this.Access : Microsoft.Azure.Batch.Common.AccessScope with get, set" Usage="Microsoft.Azure.Batch.AuthenticationTokenSettings.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.AccessScope</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトークンがアクセスを許可するバッチのリソースを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            認証トークンは、限られたサービス操作のバッチにのみアクセスを付与します。 現在、唯一サポートされている値アクセス プロパティは<see cref="F:Microsoft.Azure.Batch.Common.AccessScope.Job" />タスクが含まれているジョブに関連するすべての操作へのアクセスを付与します。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>
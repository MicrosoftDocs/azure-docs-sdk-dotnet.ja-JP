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
            <span data-ttu-id="0191c-101">バッチを実行するタスクを使用する認証トークンの設定は、操作を処理します。</span><span class="sxs-lookup"><span data-stu-id="0191c-101">The settings for an authentication token that the task can use to perform Batch service operations.</span></span>
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
            <span data-ttu-id="0191c-102"><see cref="T:Microsoft.Azure.Batch.AuthenticationTokenSettings" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0191c-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.AuthenticationTokenSettings" /> class.</span></span>
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
            <span data-ttu-id="0191c-103">取得またはトークンがアクセスを許可するバッチのリソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="0191c-103">Gets or sets the Batch resources to which the token grants access.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0191c-104">認証トークンは、限られたサービス操作のバッチにのみアクセスを付与します。</span><span class="sxs-lookup"><span data-stu-id="0191c-104">The authentication token grants access only to a limited set of Batch service operations.</span></span> <span data-ttu-id="0191c-105">現在、唯一サポートされている値アクセス プロパティは<see cref="F:Microsoft.Azure.Batch.Common.AccessScope.Job" />タスクが含まれているジョブに関連するすべての操作へのアクセスを付与します。</span><span class="sxs-lookup"><span data-stu-id="0191c-105">Currently the only supported value for the Access property is <see cref="F:Microsoft.Azure.Batch.Common.AccessScope.Job" />, which grants access to all operations related to the job which contains the task.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>
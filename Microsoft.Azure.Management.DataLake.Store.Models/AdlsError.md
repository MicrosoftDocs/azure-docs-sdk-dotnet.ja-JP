<Type Name="AdlsError" FullName="Microsoft.Azure.Management.DataLake.Store.Models.AdlsError">
  <TypeSignature Language="C#" Value="public class AdlsError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdlsError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsError" />
  <TypeSignature Language="VB.NET" Value="Public Class AdlsError" />
  <TypeSignature Language="F#" Value="type AdlsError = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            WebHDFS の特定の例外を含む data Lake Store ファイル システム エラーです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdlsError ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.AdlsError.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AdlsError クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdlsError (Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException remoteException = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException remoteException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.AdlsError.#ctor(Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional remoteException As AdlsRemoteException = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.AdlsError : Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException -&gt; Microsoft.Azure.Management.DataLake.Store.Models.AdlsError" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.AdlsError remoteException" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="remoteException" Type="Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException" />
      </Parameters>
      <Docs>
        <param name="remoteException">返される実際の WebHDFS 例外を表すオブジェクト。</param>
        <summary>
            AdlsError クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteException">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException RemoteException { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException RemoteException" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.AdlsError.RemoteException" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteException As AdlsRemoteException" />
      <MemberSignature Language="F#" Value="member this.RemoteException : Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException" Usage="Microsoft.Azure.Management.DataLake.Store.Models.AdlsError.RemoteException" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="RemoteException")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            返される実際の WebHDFS 例外イベントを表すオブジェクトを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="ResolvedServiceEndpoint" FullName="System.Fabric.ResolvedServiceEndpoint">
  <TypeSignature Language="C#" Value="public sealed class ResolvedServiceEndpoint" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ResolvedServiceEndpoint extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ResolvedServiceEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ResolvedServiceEndpoint" />
  <TypeSignature Language="F#" Value="type ResolvedServiceEndpoint = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>サービス パーティションのレプリカのロールに関する情報が含まれています、解決済みのサービスのエンドポイントとそれをリッスンするアドレスを表します。</para>
    </summary>
    <remarks>
      <para>
            解決済みのサービス エンドポイントから返される<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />の一部として<see cref="T:System.Fabric.ResolvedServicePartition" />です。
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public string Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Address" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServiceEndpoint.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As String" />
      <MemberSignature Language="F#" Value="member this.Address : string" Usage="System.Fabric.ResolvedServiceEndpoint.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>エンドポイントのアドレスを取得します。
            サービスのレプリカでは、この文字列をアクセスできるユーザーに通知 Service Fabric にできます。</para>
        </summary>
        <value>
          <para>ここでは、サービス レプリカまたはインスタンスに到達できるエンドポイントのアドレス。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Role">
      <MemberSignature Language="C#" Value="public System.Fabric.ServiceEndpointRole Role { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ServiceEndpointRole Role" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServiceEndpoint.Role" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Role As ServiceEndpointRole" />
      <MemberSignature Language="F#" Value="member this.Role : System.Fabric.ServiceEndpointRole" Usage="System.Fabric.ResolvedServiceEndpoint.Role" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServiceEndpointRole</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービス エンドポイントのロールを取得します。</para>
        </summary>
        <value>
          <para>サービス エンドポイントのロール。</para>
        </value>
        <remarks>
          <para><see cref="T:System.Fabric.ServiceEndpointRole" />クライアントによってサービス インスタンスまたはレプリカを選択しへの接続を判断するために使用します。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>
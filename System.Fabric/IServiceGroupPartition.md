<Type Name="IServiceGroupPartition" FullName="System.Fabric.IServiceGroupPartition">
  <TypeSignature Language="C#" Value="public interface IServiceGroupPartition" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceGroupPartition" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IServiceGroupPartition" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceGroupPartition" />
  <TypeSignature Language="F#" Value="type IServiceGroupPartition = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>サービス グループ内のサービス グループのメンバーは、指定されたキャストできます<see cref="T:System.Fabric.IStatefulServicePartition" />または<see cref="T:System.Fabric.IStatelessServicePartition" />を<see cref="T:System.Fabric.IServiceGroupPartition" />サービス グループ内のメンバーに固有のメソッドにアクセスします。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ResolveMember&lt;T&gt;">
      <MemberSignature Language="C#" Value="public T ResolveMember&lt;T&gt; (Uri name) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!T ResolveMember&lt;class T&gt;(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServiceGroupPartition.ResolveMember``1(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveMember(Of T As Class) (name As Uri) As T" />
      <MemberSignature Language="F#" Value="abstract member ResolveMember : Uri -&gt; 'T (requires 'T : null)" Usage="iServiceGroupPartition.ResolveMember name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <typeparam name="T">
          <para>解決する必要のあるサービス メンバーの型。</para>
        </typeparam>
        <param name="name">
          <para><c>ファブリック:/</c>解決するのには、メンバーの名前。</para>
        </param>
        <summary>
          <para>サービス グループの他のメンバーに直接アクセスを取得するメンバーを有効にします。</para>
        </summary>
        <returns>
          <para>指定した型のオブジェクトと名前で指定されているメンバーを返します。</para>
        </returns>
        <remarks>
          <para><see cref="M:System.Fabric.IServiceGroupPartition.ResolveMember``1(System.Uri)" />メソッドは、グループ内の他のメンバーへの直接参照を取得するサービス グループ メンバーを有効にします。 ダイレクト オブジェクトとの通信を他のメンバーでは、マシンまたはバーチャル マシンで、いずれかのメンバーを解決するのには名前付けサービスまたは実際に送信するいくつかの外部トランスポート経由で通信外との通信は必要ありません。メンバーにコマンド。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>
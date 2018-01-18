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
      <para><span data-ttu-id="48d1b-101">サービス グループ内のサービス グループのメンバーは、指定されたキャストできます<see cref="T:System.Fabric.IStatefulServicePartition" />または<see cref="T:System.Fabric.IStatelessServicePartition" />を<see cref="T:System.Fabric.IServiceGroupPartition" />サービス グループ内のメンバーに固有のメソッドにアクセスします。</span><span class="sxs-lookup"><span data-stu-id="48d1b-101">Service group members inside a service group can cast the provided <see cref="T:System.Fabric.IStatefulServicePartition" /> or <see cref="T:System.Fabric.IStatelessServicePartition" /> to a <see cref="T:System.Fabric.IServiceGroupPartition" /> to access the methods that are specific to members within service groups.</span></span></para>
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
          <para><span data-ttu-id="48d1b-102">解決する必要のあるサービス メンバーの型。</span><span class="sxs-lookup"><span data-stu-id="48d1b-102">The type of the service member that should be resolved.</span></span></para>
        </typeparam>
        <param name="name">
          <para><span data-ttu-id="48d1b-103"><c>ファブリック:/</c>解決するのには、メンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="48d1b-103">The <c>fabric:/</c> name of the member to resolve.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="48d1b-104">サービス グループの他のメンバーに直接アクセスを取得するメンバーを有効にします。</span><span class="sxs-lookup"><span data-stu-id="48d1b-104">Enables the member to get direct access to the other members of the service group.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="48d1b-105">指定した型のオブジェクトと名前で指定されているメンバーを返します。</span><span class="sxs-lookup"><span data-stu-id="48d1b-105">Returns the member that is specified by name as an object of the specified type.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="48d1b-106"><see cref="M:System.Fabric.IServiceGroupPartition.ResolveMember``1(System.Uri)" />メソッドは、グループ内の他のメンバーへの直接参照を取得するサービス グループ メンバーを有効にします。</span><span class="sxs-lookup"><span data-stu-id="48d1b-106">The <see cref="M:System.Fabric.IServiceGroupPartition.ResolveMember``1(System.Uri)" /> method enables a service group member to obtain a direct reference to the other members in the group.</span></span> <span data-ttu-id="48d1b-107">ダイレクト オブジェクトとの通信を他のメンバーでは、マシンまたはバーチャル マシンで、いずれかのメンバーを解決するのには名前付けサービスまたは実際に送信するいくつかの外部トランスポート経由で通信外との通信は必要ありません。メンバーにコマンド。</span><span class="sxs-lookup"><span data-stu-id="48d1b-107">The direct object-object communication with the other members does not require communication outside of the machine or virtual machine, either for communication with the Naming service to resolve the member or via some external transport to send the actual commands to the member.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>
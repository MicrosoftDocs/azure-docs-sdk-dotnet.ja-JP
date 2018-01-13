<Type Name="ServiceGroupDescription" FullName="System.Fabric.Description.ServiceGroupDescription">
  <TypeSignature Language="C#" Value="public sealed class ServiceGroupDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceGroupDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceGroupDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceGroupDescription" />
  <TypeSignature Language="F#" Value="type ServiceGroupDescription = class" />
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
      <para>作成し、サービス グループを記述するために必要な情報のコレクションを提供します。  </para>
    </summary>
    <remarks>
      <para>サービス グループの説明が含まれています、<see cref="T:System.Fabric.Description.ServiceGroupDescription" />と、サービスのグループのメンバーの一覧です。 サービスの説明は、メトリック、アプリケーション名、サービスのグループ名、およびこのサービス グループの初期化情報などの情報を提供します。 メンバーの定義の一覧には、サービスのグループ内のサービスについて説明します。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceGroupDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceGroupDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.ServiceGroupDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceGroupDescription (System.Fabric.Description.ServiceDescription serviceDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.Description.ServiceDescription serviceDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceGroupDescription.#ctor(System.Fabric.Description.ServiceDescription)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceGroupDescription : System.Fabric.Description.ServiceDescription -&gt; System.Fabric.Description.ServiceGroupDescription" Usage="new System.Fabric.Description.ServiceGroupDescription serviceDescription" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceDescription" Type="System.Fabric.Description.ServiceDescription" />
      </Parameters>
      <Docs>
        <param name="serviceDescription">
          <para><see cref="T:System.Fabric.Description.ServiceDescription" />の基礎として使用する、<see cref="T:System.Fabric.Description.ServiceGroupDescription" />です。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Description.ServiceGroupDescription" /> を指定して、<see cref="T:System.Fabric.Description.ServiceDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MemberDescriptions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceGroupMemberDescription&gt; MemberDescriptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ServiceGroupMemberDescription&gt; MemberDescriptions" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupDescription.MemberDescriptions" />
      <MemberSignature Language="VB.NET" Value="Public Property MemberDescriptions As IList(Of ServiceGroupMemberDescription)" />
      <MemberSignature Language="F#" Value="member this.MemberDescriptions : System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceGroupMemberDescription&gt; with get, set" Usage="System.Fabric.Description.ServiceGroupDescription.MemberDescriptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceGroupMemberDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>リストを示す<see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" />このサービス グループのメンバーのオブジェクト。</para>
        </summary>
        <value>
          <para>返します<see cref="T:System.Collections.Generic.IList`1" />型の<see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" />します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceDescription">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServiceDescription ServiceDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.ServiceDescription ServiceDescription" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupDescription.ServiceDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceDescription As ServiceDescription" />
      <MemberSignature Language="F#" Value="member this.ServiceDescription : System.Fabric.Description.ServiceDescription with get, set" Usage="System.Fabric.Description.ServiceGroupDescription.ServiceDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービス グループのサービスについて説明します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Description.ServiceDescription" /> を返します。</para>
        </value>
        <remarks>
          <para>サービスの説明では、システムで、キー、キーの範囲およびその他のプロパティなど、パーティション スキームを含む、サービス グループをパーティション分割方法について説明します。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>
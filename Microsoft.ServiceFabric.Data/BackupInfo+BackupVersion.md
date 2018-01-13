<Type Name="BackupInfo+BackupVersion" FullName="Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion">
  <TypeSignature Language="C#" Value="public struct BackupInfo.BackupVersion : IComparable&lt;Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion&gt;, IEquatable&lt;Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion&gt;" />
  <TypeSignature Language="ILAsm" Value=".class nested public sequential ansi sealed beforefieldinit BackupInfo/BackupVersion extends System.ValueType implements class System.IComparable`1&lt;valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion&gt;, class System.IEquatable`1&lt;valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion" />
  <TypeSignature Language="VB.NET" Value="Public Structure BackupInfo.BackupVersion&#xA;Implements IComparable(Of BackupInfo.BackupVersion), IEquatable(Of BackupInfo.BackupVersion)" />
  <TypeSignature Language="F#" Value="type BackupInfo.BackupVersion = struct" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ValueType</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IComparable&lt;Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Performance", "CA1815")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            バックアップのバージョンを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupVersion (System.Fabric.Epoch epoch, long lsn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Epoch epoch, int64 lsn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.#ctor(System.Fabric.Epoch,System.Int64)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion : System.Fabric.Epoch * int64 -&gt; Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion" Usage="new Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion (epoch, lsn)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="epoch" Type="System.Fabric.Epoch" />
        <Parameter Name="lsn" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="epoch"><cref name="Epoch" />で、バックアップが作成されました。</param>
        <param name="lsn">バックアップに含まれる論理シーケンス番号を最後にコミットされます。</param>
        <summary>
            新しいインスタンスを初期化します<cref name="BackupVersion" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompareTo">
      <MemberSignature Language="C#" Value="public int CompareTo (Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 CompareTo(valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.CompareTo(Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompareTo (other As BackupInfo.BackupVersion) As Integer" />
      <MemberSignature Language="F#" Value="abstract member CompareTo : Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion -&gt; int&#xA;override this.CompareTo : Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion -&gt; int" Usage="backupVersion.CompareTo other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IComparable`1.CompareTo(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion" />
      </Parameters>
      <Docs>
        <param name="other"><cref name="BackupVersion" /> に評価されるオブジェクト。</param>
        <summary>
            このインスタンスと指定した比較<cref name="BackupVersion" />オブジェクトをこのインスタンスについてよりも前、後ろ、または、指定された並べ替え順序内の同じ位置に表示されますでかどうかを示す<cref name="BackupVersion" />です。 
            </summary>
        <returns>
            比較対象オブジェクトの相対順序を示す値。
            0 は、このインスタンスでの前に他の並べ替え順序を示しますよりも少ない。
            0 は、このインスタンスが他の並べ替え順序内の同じ位置で発生することを示します。 以上を指定するとゼロでは、このインスタンスに従っているその他の並べ替え順序のことを示します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Epoch">
      <MemberSignature Language="C#" Value="public System.Fabric.Epoch Epoch { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Epoch Epoch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.Epoch" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Epoch As Epoch" />
      <MemberSignature Language="F#" Value="member this.Epoch : System.Fabric.Epoch" Usage="Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.Epoch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Epoch</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<cref name="Epoch" />で、バックアップが作成されました。
            </summary>
        <value><cref name="Epoch" />で、バックアップが作成されました。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.Equals(Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As BackupInfo.BackupVersion) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion -&gt; bool" Usage="backupVersion.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion" />
      </Parameters>
      <Docs>
        <param name="other"><cref name="BackupVersion" />このインスタンスと比較します。 </param>
        <summary>
            このインスタンスと、指定した別の <cref name="BackupVersion" /> の値が同一かどうかを判断します。
            </summary>
        <returns>
            value パラメーターの値がこのインスタンスの値と同じである場合は trueそれ以外の場合は false です。 
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="backupVersion.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><cref name="BackupVersion" />このインスタンスと比較します。 </param>
        <summary>
            このインスタンスと、指定した別の <cref name="BackupVersion" /> の値が同一かどうかを判断します。
            </summary>
        <returns>
            value パラメーターの値がこのインスタンスの値と同じである場合は trueそれ以外の場合は false です。 
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="backupVersion.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            この <cref name="BackupVersion" /> のハッシュ コードを返します。
            </summary>
        <returns>
            32 ビット符号付き整数ハッシュ コード。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvalidBackupVersion">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion InvalidBackupVersion;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion InvalidBackupVersion" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.InvalidBackupVersion" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly InvalidBackupVersion As BackupInfo.BackupVersion " />
      <MemberSignature Language="F#" Value=" staticval mutable InvalidBackupVersion : Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion" Usage="Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.InvalidBackupVersion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            バックアップのバージョンが無効です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lsn">
      <MemberSignature Language="C#" Value="public long Lsn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Lsn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.Lsn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Lsn As Long" />
      <MemberSignature Language="F#" Value="member this.Lsn : int64" Usage="Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.Lsn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得最後にコミットしたバックアップに含まれる論理シーケンス番号。
            </summary>
        <value>バックアップに含まれる論理シーケンス番号を最後にコミットされます。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>